# Руководство по использованию UI Engine

## Основные типы элементов
UI Engine предоставляет несколько типов элементов для создания пользовательских интерфейсов в Minecraft. Эти элементы можно использовать напрямую или наследовать от них для создания собственных компонентов.

### AbstractElement
Все элементы наследуются от `AbstractElement`, который предоставляет базовые свойства и методы для работы с UI.

#### offset
Управление положением элементов осуществляется с помощью сдвигов по пикселям.

Пример:
```kotlin
offset = V3(1.0, 2.0) // сдвинет элемент на 1 пиксель вправо и на 2 пикселя вниз
```

Для точного расположения элементов на экране используйте свойства `align`, `origin` и `padding`.

#### align
Сдвиг элемента в процентах относительно родителя (или экрана).

Основной концепт UI Engine - использование `align` и `origin` для адаптивного дизайна интерфейсов. Они помогают адаптировать UI для разных размеров экрана и интерфейса.

Пример:
```kotlin
align = Relative.CENTER // Центрирование элемента относительно родителя
```

#### origin
Сдвиг элемента в процентах относительно самого себя.

`origin` определяет точку привязки элемента к родителю. По умолчанию, `origin` равен `Relative.TOP_LEFT`, что означает привязку левого верхнего угла элемента к родителю.

Пример:
```kotlin
align = Relative.CENTER
origin = Relative.CENTER // Центрирование элемента по обеим осям
```

#### color
Изменение цвета элементов.

UI Engine предоставляет три предустановленных цвета: `TRANSPARENT`, `BLACK` и `WHITE`. Вы также можете создавать свои цвета.

Пример:
```kotlin
element.color = Color(red = 255, green = 100, blue = 0, alpha = 0.5) // Создание цвета
element.color.alpha = 1.0 // Изменение альфа-канала
element.color = WHITE // Установка белого цвета
```

### RectangleElement
Двухмерные прямоугольники, которые могут содержать дочерние элементы.

#### size
Задает размер прямоугольника в пикселях.

Пример:
```kotlin
size = V3(100.0, 50.0) // Размер прямоугольника
```

#### children
`RectangleElement` может содержать дочерние элементы, используя методы `addChild(...)` и `removeChild(...)`.

Пример:
```kotlin
val element = RectangleElement {
    size = V3(100.0, 50.0)
    color = BLACK
    align = Relative.CENTER
    origin = Relative.CENTER
    addChild(TextElement {
        content = "Привет, мир!"
        align = Relative.TOP_LEFT
    })
}
UIManager.addElement(element)
```
Этот код добавляет в центр экрана прямоугольник с текстом "Привет, мир!" в его левом верхнем углу.

### TextureElement
Элемент для отображения текстур.

#### texturePath
Путь к текстуре.

#### textureWidth и textureHeight
Размеры текстуры в пикселях, по умолчанию 16x16.

Пример:
```kotlin
val element = TextureElement {
    texturePath = Identifier("minecraft", "textures/gui/container/inventory.png")
    textureWidth = 256
    textureHeight = 256
    align = Relative.CENTER
}
UIManager.addElement(element)
```
Этот код добавляет текстуру инвентаря в центр экрана.

### TextElement
Элемент для отображения текста.

#### content
Содержимое текста.

#### autoFit
Если включено, текст будет автоматически подгоняться под ширину родителя.

Пример:
```kotlin
val textElement = TextElement {
    content = "Hello, Minecraft!"
    autoFit = true
}
```
Этот элемент отобразит текст "Hello, Minecraft!" и автоматически подгонит его размер под ширину родителя при включенном `autoFit`. (Экспериментальная функция, возможны проблемы)
