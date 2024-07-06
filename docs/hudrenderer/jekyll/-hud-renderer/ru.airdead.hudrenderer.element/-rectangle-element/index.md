---
title: RectangleElement
---
//[HudRenderer](../../../index.html)/[ru.airdead.hudrenderer.element](../index.html)/[RectangleElement](index.html)



# RectangleElement



[jvm]\
open class [RectangleElement](index.html) : [AbstractElement](../-abstract-element/index.html), [Parent](../-parent/index.html)

Class representing a rectangle element. Inherits from [AbstractElement](../-abstract-element/index.html) and implements the [Parent](../-parent/index.html) interface.



## Constructors


| | |
|---|---|
| [RectangleElement](-rectangle-element.html) | [jvm]<br>constructor() |


## Properties


| Name | Summary |
|---|---|
| [align](../-abstract-element/align.html) | [jvm]<br>var [align](../-abstract-element/align.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The alignment of this element. |
| [children](children.html) | [jvm]<br>open override val [children](children.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[AbstractElement](../-abstract-element/index.html)&gt;<br>The list of child elements. |
| [color](../-abstract-element/color.html) | [jvm]<br>open var [color](../-abstract-element/color.html): [Color](../../ru.airdead.hudrenderer.utility/-color/index.html)<br>The color of this element. |
| [enabled](../-abstract-element/enabled.html) | [jvm]<br>open var [enabled](../-abstract-element/enabled.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates whether the element is enabled. If disabled, the element will not be interactable. |
| [interactable](../-abstract-element/interactable.html) | [jvm]<br>open var [interactable](../-abstract-element/interactable.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates whether the element is interactable. If the element is disabled, it cannot be interactable. |
| [lastParent](../-abstract-element/last-parent.html) | [jvm]<br>var [lastParent](../-abstract-element/last-parent.html): [AbstractElement](../-abstract-element/index.html)?<br>The last parent element of this element. |
| [mask](mask.html) | [jvm]<br>var [mask](mask.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates whether masking is enabled. |
| [offset](../-abstract-element/offset.html) | [jvm]<br>var [offset](../-abstract-element/offset.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The offset of this element from its original position. |
| [origin](../-abstract-element/origin.html) | [jvm]<br>var [origin](../-abstract-element/origin.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The origin point of this element. |
| [regionSize](region-size.html) | [jvm]<br>var [regionSize](region-size.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The size of the region to be rendered from the texture. |
| [renderLocation](../-abstract-element/render-location.html) | [jvm]<br>var [renderLocation](../-abstract-element/render-location.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The render location of this element in 3D space. |
| [rotation](../-abstract-element/rotation.html) | [jvm]<br>var [rotation](../-abstract-element/rotation.html): [Rotation](../../ru.airdead.hudrenderer.utility/-rotation/index.html)<br>The rotation of this element. |
| [size](../-abstract-element/size.html) | [jvm]<br>open override var [size](../-abstract-element/size.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The size of this element. |
| [texture](texture.html) | [jvm]<br>var [texture](texture.html): Identifier?<br>The texture to be applied to the rectangle. |
| [textureSize](texture-size.html) | [jvm]<br>var [textureSize](texture-size.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The actual size of the texture. |


## Functions


| Name | Summary |
|---|---|
| [addChild](../-parent/add-child.html) | [jvm]<br>open fun [addChild](../-parent/add-child.html)(vararg elements: [AbstractElement](../-abstract-element/index.html))<br>Adds multiple child elements to the parent.<br>[jvm]<br>open fun [addChild](../-parent/add-child.html)(element: [AbstractElement](../-abstract-element/index.html))<br>Adds a child element to the parent. |
| [handleMouseClick](../-abstract-element/handle-mouse-click.html) | [jvm]<br>open fun [handleMouseClick](../-abstract-element/handle-mouse-click.html)(button: [MouseButton](../../ru.airdead.hudrenderer.utility/-mouse-button/index.html), pressed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Handles mouse click events. |
| [handleMouseHover](../-abstract-element/handle-mouse-hover.html) | [jvm]<br>open fun [handleMouseHover](../-abstract-element/handle-mouse-hover.html)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Handles mouse hover events. |
| [isHovered](../-abstract-element/is-hovered.html) | [jvm]<br>fun [isHovered](../-abstract-element/is-hovered.html)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the element is hovered based on the mouse coordinates. |
| [onClick](../-abstract-element/on-click.html) | [jvm]<br>fun [onClick](../-abstract-element/on-click.html)(handler: [ClickHandler](../../ru.airdead.hudrenderer.utility/-click-handler/index.html))<br>Sets a handler for click events. |
| [onHover](../-abstract-element/on-hover.html) | [jvm]<br>fun [onHover](../-abstract-element/on-hover.html)(handler: [HoverHandler](../../ru.airdead.hudrenderer.utility/-hover-handler/index.html))<br>Sets a handler for hover events. |
| [plus](../-parent/plus.html) | [jvm]<br>open operator fun &lt;[T](../-parent/plus.html) : [AbstractElement](../-abstract-element/index.html)&gt; [plus](../-parent/plus.html)(element: [T](../-parent/plus.html)): [T](../-parent/plus.html)<br>Adds a child element to the parent using the plus operator. |
| [removeChild](../-parent/remove-child.html) | [jvm]<br>open fun [removeChild](../-parent/remove-child.html)(vararg elements: [AbstractElement](../-abstract-element/index.html))<br>Removes multiple child elements from the parent.<br>[jvm]<br>open fun [removeChild](../-parent/remove-child.html)(element: [AbstractElement](../-abstract-element/index.html))<br>Removes a child element from the parent. |
| [render](render.html) | [jvm]<br>open override fun [render](render.html)(drawContext: DrawContext, tickDelta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Renders the rectangle element. |
| [transformAndRender](../-abstract-element/transform-and-render.html) | [jvm]<br>fun [transformAndRender](../-abstract-element/transform-and-render.html)(drawContext: DrawContext, tickDelta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Transforms and renders the element. |
| [unaryPlus](../-parent/unary-plus.html) | [jvm]<br>open operator fun &lt;[T](../-parent/unary-plus.html) : [AbstractElement](../-abstract-element/index.html)&gt; [T](../-parent/unary-plus.html).[unaryPlus](../-parent/unary-plus.html)(): [T](../-parent/unary-plus.html)<br>Adds a child element to the parent using the unary plus operator. |

