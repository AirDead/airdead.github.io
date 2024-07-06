---
title: ru.airdead.hudrenderer.utility
---
//[HudRenderer](../../index.html)/[ru.airdead.hudrenderer.utility](index.html)



# Package-level declarations



## Types


| Name | Summary |
|---|---|
| [ButtonContext](-button-context/index.html) | [jvm]<br>data class [ButtonContext](-button-context/index.html)(val key: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val modifiers: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)&lt;[Modifiers](-modifiers/index.html)&gt;) |
| [ButtonHandler](-button-handler/index.html) | [jvm]<br>typealias [ButtonHandler](-button-handler/index.html) = [ButtonContext](-button-context/index.html).() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [ClickContext](-click-context/index.html) | [jvm]<br>data class [ClickContext](-click-context/index.html)(val button: [MouseButton](-mouse-button/index.html), val isPressed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Data class representing the context of a click event. |
| [ClickHandler](-click-handler/index.html) | [jvm]<br>typealias [ClickHandler](-click-handler/index.html) = [ClickContext](-click-context/index.html).() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Type alias for a handler function that processes click context. |
| [Color](-color/index.html) | [jvm]<br>open class [Color](-color/index.html)(var red: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, var green: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, var blue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, var alpha: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0)<br>Class representing a color with red, green, blue, and alpha (transparency) components. |
| [ElementBuilderDsl](-element-builder-dsl/index.html) | [jvm]<br>@[DslMarker](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-dsl-marker/index.html)<br>annotation class [ElementBuilderDsl](-element-builder-dsl/index.html) |
| [HoverContext](-hover-context/index.html) | [jvm]<br>data class [HoverContext](-hover-context/index.html)(val isHovered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Data class representing the context of a hover event. |
| [HoverHandler](-hover-handler/index.html) | [jvm]<br>typealias [HoverHandler](-hover-handler/index.html) = [HoverContext](-hover-context/index.html).() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Type alias for a handler function that processes hover context. |
| [Modifiers](-modifiers/index.html) | [jvm]<br>enum [Modifiers](-modifiers/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[Modifiers](-modifiers/index.html)&gt; |
| [MouseButton](-mouse-button/index.html) | [jvm]<br>enum [MouseButton](-mouse-button/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[MouseButton](-mouse-button/index.html)&gt; |
| [Relative](-relative/index.html) | [jvm]<br>object [Relative](-relative/index.html)<br>Object containing predefined relative positions for alignment and anchoring. |
| [Rotation](-rotation/index.html) | [jvm]<br>open class [Rotation](-rotation/index.html)(val degrees: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [ScrollContext](-scroll-context/index.html) | [jvm]<br>data class [ScrollContext](-scroll-context/index.html)(val hoveredElement: [AbstractElement](../ru.airdead.hudrenderer.element/-abstract-element/index.html)?, val amount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [ScrollDirection](-scroll-direction/index.html) | [jvm]<br>enum [ScrollDirection](-scroll-direction/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[ScrollDirection](-scroll-direction/index.html)&gt; |
| [ScrollHandler](-scroll-handler/index.html) | [jvm]<br>typealias [ScrollHandler](-scroll-handler/index.html) = [ScrollContext](-scroll-context/index.html).() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [V2](-v2/index.html) | [jvm]<br>open class [V2](-v2/index.html)(val x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, val y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0) |
| [V3](-v3/index.html) | [jvm]<br>open class [V3](-v3/index.html)(val x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), val z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0) : [V2](-v2/index.html) |


## Properties


| Name | Summary |
|---|---|
| [BLACK](-b-l-a-c-k.html) | [jvm]<br>@[JvmField](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-field/index.html)<br>val [BLACK](-b-l-a-c-k.html): [Color](-color/index.html) |
| [BOTTOM](-b-o-t-t-o-m.html) | [jvm]<br>@[JvmField](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-field/index.html)<br>val [BOTTOM](-b-o-t-t-o-m.html): [V3](-v3/index.html) |
| [BOTTOM_LEFT](-b-o-t-t-o-m_-l-e-f-t.html) | [jvm]<br>@[JvmField](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-field/index.html)<br>val [BOTTOM_LEFT](-b-o-t-t-o-m_-l-e-f-t.html): [V3](-v3/index.html) |
| [BOTTOM_RIGHT](-b-o-t-t-o-m_-r-i-g-h-t.html) | [jvm]<br>@[JvmField](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-field/index.html)<br>val [BOTTOM_RIGHT](-b-o-t-t-o-m_-r-i-g-h-t.html): [V3](-v3/index.html) |
| [CENTER](-c-e-n-t-e-r.html) | [jvm]<br>@[JvmField](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-field/index.html)<br>val [CENTER](-c-e-n-t-e-r.html): [V3](-v3/index.html) |
| [LEFT](-l-e-f-t.html) | [jvm]<br>@[JvmField](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-field/index.html)<br>val [LEFT](-l-e-f-t.html): [V3](-v3/index.html) |
| [RIGHT](-r-i-g-h-t.html) | [jvm]<br>@[JvmField](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-field/index.html)<br>val [RIGHT](-r-i-g-h-t.html): [V3](-v3/index.html) |
| [TOP](-t-o-p.html) | [jvm]<br>@[JvmField](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-field/index.html)<br>val [TOP](-t-o-p.html): [V3](-v3/index.html) |
| [TOP_LEFT](-t-o-p_-l-e-f-t.html) | [jvm]<br>@[JvmField](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-field/index.html)<br>val [TOP_LEFT](-t-o-p_-l-e-f-t.html): [V3](-v3/index.html)<br>Predefined positions for alignment and anchoring. |
| [TOP_RIGHT](-t-o-p_-r-i-g-h-t.html) | [jvm]<br>@[JvmField](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-field/index.html)<br>val [TOP_RIGHT](-t-o-p_-r-i-g-h-t.html): [V3](-v3/index.html) |
| [TRANSPARENT](-t-r-a-n-s-p-a-r-e-n-t.html) | [jvm]<br>@[JvmField](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-field/index.html)<br>val [TRANSPARENT](-t-r-a-n-s-p-a-r-e-n-t.html): [Color](-color/index.html) |
| [WHITE](-w-h-i-t-e.html) | [jvm]<br>@[JvmField](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-field/index.html)<br>val [WHITE](-w-h-i-t-e.html): [Color](-color/index.html)<br>Predefined color constants. |


## Functions


| Name | Summary |
|---|---|
| [beautifulRectangle](beautiful-rectangle.html) | [jvm]<br>inline fun [beautifulRectangle](beautiful-rectangle.html)(setup: [BeautifulRectangleElement](../ru.airdead.hudrenderer.element/-beautiful-rectangle-element/index.html).() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [BeautifulRectangleElement](../ru.airdead.hudrenderer.element/-beautiful-rectangle-element/index.html)<br>Inline function to create and configure a [BeautifulRectangleElement](../ru.airdead.hudrenderer.element/-beautiful-rectangle-element/index.html). |
| [menu](menu.html) | [jvm]<br>inline fun [menu](menu.html)(setup: [ContextMenu](../ru.airdead.hudrenderer.element/-context-menu/index.html).() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [ContextMenu](../ru.airdead.hudrenderer.element/-context-menu/index.html)<br>Inline function to create and configure a [ContextMenu](../ru.airdead.hudrenderer.element/-context-menu/index.html). |
| [rectangle](rectangle.html) | [jvm]<br>inline fun [rectangle](rectangle.html)(setup: [RectangleElement](../ru.airdead.hudrenderer.element/-rectangle-element/index.html).() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [RectangleElement](../ru.airdead.hudrenderer.element/-rectangle-element/index.html)<br>Inline function to create and configure a [RectangleElement](../ru.airdead.hudrenderer.element/-rectangle-element/index.html). |
| [text](text.html) | [jvm]<br>inline fun [text](text.html)(setup: [TextElement](../ru.airdead.hudrenderer.element/-text-element/index.html).() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [TextElement](../ru.airdead.hudrenderer.element/-text-element/index.html)<br>Inline function to create and configure a [TextElement](../ru.airdead.hudrenderer.element/-text-element/index.html). |

