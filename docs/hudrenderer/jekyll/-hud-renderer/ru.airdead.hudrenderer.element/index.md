---
title: ru.airdead.hudrenderer.element
---
//[HudRenderer](../../index.html)/[ru.airdead.hudrenderer.element](index.html)



# Package-level declarations



## Types


| Name | Summary |
|---|---|
| [AbstractElement](-abstract-element/index.html) | [jvm]<br>abstract class [AbstractElement](-abstract-element/index.html) : [IElement](-i-element/index.html)<br>Abstract base class representing a UI element in the UIEngine. Implements the [IElement](-i-element/index.html) interface. |
| [BeautifulRectangleElement](-beautiful-rectangle-element/index.html) | [jvm]<br>open class [BeautifulRectangleElement](-beautiful-rectangle-element/index.html) : [AbstractElement](-abstract-element/index.html), [Parent](-parent/index.html)<br>Class representing a rectangle element with rounded corners and optional texture. Inherits from [AbstractElement](-abstract-element/index.html) and implements the [Parent](-parent/index.html) interface. |
| [ContextMenu](-context-menu/index.html) | [jvm]<br>class [ContextMenu](-context-menu/index.html) : [AbstractElement](-abstract-element/index.html), [Parent](-parent/index.html)<br>Class representing a context menu. Inherits from [AbstractElement](-abstract-element/index.html) and implements the [Parent](-parent/index.html) interface. |
| [DragContext](-drag-context/index.html) | [jvm]<br>data class [DragContext](-drag-context/index.html)(val element: [AbstractElement](-abstract-element/index.html), val mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val dx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val dy: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Data class representing the context of a drag event. |
| [DragHandler](-drag-handler/index.html) | [jvm]<br>typealias [DragHandler](-drag-handler/index.html) = ([DragContext](-drag-context/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [IElement](-i-element/index.html) | [jvm]<br>interface [IElement](-i-element/index.html) |
| [Parent](-parent/index.html) | [jvm]<br>interface [Parent](-parent/index.html) : [IElement](-i-element/index.html)<br>Interface representing a parent element in the UI. Inherits from [IElement](-i-element/index.html). |
| [RectangleElement](-rectangle-element/index.html) | [jvm]<br>open class [RectangleElement](-rectangle-element/index.html) : [AbstractElement](-abstract-element/index.html), [Parent](-parent/index.html)<br>Class representing a rectangle element. Inherits from [AbstractElement](-abstract-element/index.html) and implements the [Parent](-parent/index.html) interface. |
| [TextElement](-text-element/index.html) | [jvm]<br>class [TextElement](-text-element/index.html) : [AbstractElement](-abstract-element/index.html)<br>Class representing a text element. Inherits from [AbstractElement](-abstract-element/index.html). |

