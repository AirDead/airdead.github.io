---
title: ContextMenu
---
//[HudRenderer](../../../index.html)/[ru.airdead.hudrenderer.element](../index.html)/[ContextMenu](index.html)



# ContextMenu



[jvm]\
class [ContextMenu](index.html) : [AbstractElement](../-abstract-element/index.html), [Parent](../-parent/index.html)

Class representing a context menu. Inherits from [AbstractElement](../-abstract-element/index.html) and implements the [Parent](../-parent/index.html) interface.



## Constructors


| | |
|---|---|
| [ContextMenu](-context-menu.html) | [jvm]<br>constructor() |


## Properties


| Name | Summary |
|---|---|
| [align](../-abstract-element/align.html) | [jvm]<br>var [align](../-abstract-element/align.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The alignment of this element. |
| [children](children.html) | [jvm]<br>open override val [children](children.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[AbstractElement](../-abstract-element/index.html)&gt;<br>The list of child elements. |
| [color](color.html) | [jvm]<br>open override var [color](color.html): [Color](../../ru.airdead.hudrenderer.utility/-color/index.html)<br>The color of the context menu. |
| [enabled](enabled.html) | [jvm]<br>open override var [enabled](enabled.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates whether the context menu is enabled. |
| [interactable](interactable.html) | [jvm]<br>open override var [interactable](interactable.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates whether the context menu is interactable. |
| [lastParent](../-abstract-element/last-parent.html) | [jvm]<br>var [lastParent](../-abstract-element/last-parent.html): [AbstractElement](../-abstract-element/index.html)?<br>The last parent element of this element. |
| [offset](../-abstract-element/offset.html) | [jvm]<br>var [offset](../-abstract-element/offset.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The offset of this element from its original position. |
| [origin](../-abstract-element/origin.html) | [jvm]<br>var [origin](../-abstract-element/origin.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The origin point of this element. |
| [renderLocation](../-abstract-element/render-location.html) | [jvm]<br>var [renderLocation](../-abstract-element/render-location.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The render location of this element in 3D space. |
| [rotation](../-abstract-element/rotation.html) | [jvm]<br>var [rotation](../-abstract-element/rotation.html): [Rotation](../../ru.airdead.hudrenderer.utility/-rotation/index.html)<br>The rotation of this element. |
| [size](../-abstract-element/size.html) | [jvm]<br>open override var [size](../-abstract-element/size.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The size of this element. |


## Functions


| Name | Summary |
|---|---|
| [addChild](../-parent/add-child.html) | [jvm]<br>open fun [addChild](../-parent/add-child.html)(vararg elements: [AbstractElement](../-abstract-element/index.html))<br>Adds multiple child elements to the parent.<br>[jvm]<br>open fun [addChild](../-parent/add-child.html)(element: [AbstractElement](../-abstract-element/index.html))<br>Adds a child element to the parent. |
| [handleDrag](handle-drag.html) | [jvm]<br>fun [handleDrag](handle-drag.html)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dy: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Handles drag events. |
| [handleKeyPressed](handle-key-pressed.html) | [jvm]<br>fun [handleKeyPressed](handle-key-pressed.html)(keyCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), modifiers: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)&lt;[Modifiers](../../ru.airdead.hudrenderer.utility/-modifiers/index.html)&gt;)<br>Handles key press events. |
| [handleMouseClick](../-abstract-element/handle-mouse-click.html) | [jvm]<br>open fun [handleMouseClick](../-abstract-element/handle-mouse-click.html)(button: [MouseButton](../../ru.airdead.hudrenderer.utility/-mouse-button/index.html), pressed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Handles mouse click events. |
| [handleMouseHover](../-abstract-element/handle-mouse-hover.html) | [jvm]<br>open fun [handleMouseHover](../-abstract-element/handle-mouse-hover.html)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Handles mouse hover events. |
| [handleScroll](handle-scroll.html) | [jvm]<br>fun [handleScroll](handle-scroll.html)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), amount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Handles scroll events. |
| [hide](hide.html) | [jvm]<br>fun [hide](hide.html)()<br>Hides the context menu and restores the chat visibility. |
| [isHovered](../-abstract-element/is-hovered.html) | [jvm]<br>fun [isHovered](../-abstract-element/is-hovered.html)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the element is hovered based on the mouse coordinates. |
| [onClick](../-abstract-element/on-click.html) | [jvm]<br>fun [onClick](../-abstract-element/on-click.html)(handler: [ClickHandler](../../ru.airdead.hudrenderer.utility/-click-handler/index.html))<br>Sets a handler for click events. |
| [onDrag](on-drag.html) | [jvm]<br>fun [onDrag](on-drag.html)(handler: [DragHandler](../-drag-handler/index.html))<br>Sets a handler for drag events. |
| [onHover](../-abstract-element/on-hover.html) | [jvm]<br>fun [onHover](../-abstract-element/on-hover.html)(handler: [HoverHandler](../../ru.airdead.hudrenderer.utility/-hover-handler/index.html))<br>Sets a handler for hover events. |
| [onKeyPressed](on-key-pressed.html) | [jvm]<br>fun [onKeyPressed](on-key-pressed.html)(action: [ButtonHandler](../../ru.airdead.hudrenderer.utility/-button-handler/index.html))<br>Sets a handler for key press events. |
| [onScroll](on-scroll.html) | [jvm]<br>fun [onScroll](on-scroll.html)(handler: [ScrollHandler](../../ru.airdead.hudrenderer.utility/-scroll-handler/index.html))<br>Sets a handler for scroll events. |
| [plus](../-parent/plus.html) | [jvm]<br>open operator fun &lt;[T](../-parent/plus.html) : [AbstractElement](../-abstract-element/index.html)&gt; [plus](../-parent/plus.html)(element: [T](../-parent/plus.html)): [T](../-parent/plus.html)<br>Adds a child element to the parent using the plus operator. |
| [removeChild](../-parent/remove-child.html) | [jvm]<br>open fun [removeChild](../-parent/remove-child.html)(vararg elements: [AbstractElement](../-abstract-element/index.html))<br>Removes multiple child elements from the parent.<br>[jvm]<br>open fun [removeChild](../-parent/remove-child.html)(element: [AbstractElement](../-abstract-element/index.html))<br>Removes a child element from the parent. |
| [render](render.html) | [jvm]<br>open override fun [render](render.html)(drawContext: DrawContext, tickDelta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Renders the context menu. |
| [show](show.html) | [jvm]<br>fun [show](show.html)()<br>Shows the context menu and hides the chat. |
| [transformAndRender](../-abstract-element/transform-and-render.html) | [jvm]<br>fun [transformAndRender](../-abstract-element/transform-and-render.html)(drawContext: DrawContext, tickDelta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Transforms and renders the element. |
| [unaryPlus](../-parent/unary-plus.html) | [jvm]<br>open operator fun &lt;[T](../-parent/unary-plus.html) : [AbstractElement](../-abstract-element/index.html)&gt; [T](../-parent/unary-plus.html).[unaryPlus](../-parent/unary-plus.html)(): [T](../-parent/unary-plus.html)<br>Adds a child element to the parent using the unary plus operator. |

