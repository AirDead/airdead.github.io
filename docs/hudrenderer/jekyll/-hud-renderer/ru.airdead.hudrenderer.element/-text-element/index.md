---
title: TextElement
---
//[HudRenderer](../../../index.html)/[ru.airdead.hudrenderer.element](../index.html)/[TextElement](index.html)



# TextElement



[jvm]\
class [TextElement](index.html) : [AbstractElement](../-abstract-element/index.html)

Class representing a text element. Inherits from [AbstractElement](../-abstract-element/index.html).



## Constructors


| | |
|---|---|
| [TextElement](-text-element.html) | [jvm]<br>constructor() |


## Properties


| Name | Summary |
|---|---|
| [align](../-abstract-element/align.html) | [jvm]<br>var [align](../-abstract-element/align.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The alignment of this element. |
| [autoFit](auto-fit.html) | [jvm]<br>var [autoFit](auto-fit.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates whether the text element should automatically fit its content. When enabled, the size is updated based on the content. |
| [color](../-abstract-element/color.html) | [jvm]<br>open var [color](../-abstract-element/color.html): [Color](../../ru.airdead.hudrenderer.utility/-color/index.html)<br>The color of this element. |
| [content](content.html) | [jvm]<br>var [content](content.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The content of the text element. When the content is updated, the size is also updated. |
| [enabled](../-abstract-element/enabled.html) | [jvm]<br>open var [enabled](../-abstract-element/enabled.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates whether the element is enabled. If disabled, the element will not be interactable. |
| [interactable](../-abstract-element/interactable.html) | [jvm]<br>open var [interactable](../-abstract-element/interactable.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates whether the element is interactable. If the element is disabled, it cannot be interactable. |
| [lastParent](../-abstract-element/last-parent.html) | [jvm]<br>var [lastParent](../-abstract-element/last-parent.html): [AbstractElement](../-abstract-element/index.html)?<br>The last parent element of this element. |
| [offset](../-abstract-element/offset.html) | [jvm]<br>var [offset](../-abstract-element/offset.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The offset of this element from its original position. |
| [origin](../-abstract-element/origin.html) | [jvm]<br>var [origin](../-abstract-element/origin.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The origin point of this element. |
| [renderLocation](../-abstract-element/render-location.html) | [jvm]<br>var [renderLocation](../-abstract-element/render-location.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The render location of this element in 3D space. |
| [rotation](../-abstract-element/rotation.html) | [jvm]<br>var [rotation](../-abstract-element/rotation.html): [Rotation](../../ru.airdead.hudrenderer.utility/-rotation/index.html)<br>The rotation of this element. |
| [shadow](shadow.html) | [jvm]<br>var [shadow](shadow.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates whether the text should be drawn with a shadow. |
| [size](../-abstract-element/size.html) | [jvm]<br>open override var [size](../-abstract-element/size.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The size of this element. |


## Functions


| Name | Summary |
|---|---|
| [handleMouseClick](../-abstract-element/handle-mouse-click.html) | [jvm]<br>open fun [handleMouseClick](../-abstract-element/handle-mouse-click.html)(button: [MouseButton](../../ru.airdead.hudrenderer.utility/-mouse-button/index.html), pressed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Handles mouse click events. |
| [handleMouseHover](../-abstract-element/handle-mouse-hover.html) | [jvm]<br>open fun [handleMouseHover](../-abstract-element/handle-mouse-hover.html)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Handles mouse hover events. |
| [isHovered](../-abstract-element/is-hovered.html) | [jvm]<br>fun [isHovered](../-abstract-element/is-hovered.html)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the element is hovered based on the mouse coordinates. |
| [onClick](../-abstract-element/on-click.html) | [jvm]<br>fun [onClick](../-abstract-element/on-click.html)(handler: [ClickHandler](../../ru.airdead.hudrenderer.utility/-click-handler/index.html))<br>Sets a handler for click events. |
| [onHover](../-abstract-element/on-hover.html) | [jvm]<br>fun [onHover](../-abstract-element/on-hover.html)(handler: [HoverHandler](../../ru.airdead.hudrenderer.utility/-hover-handler/index.html))<br>Sets a handler for hover events. |
| [render](render.html) | [jvm]<br>open override fun [render](render.html)(drawContext: DrawContext, tickDelta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Renders the text element. |
| [transformAndRender](../-abstract-element/transform-and-render.html) | [jvm]<br>fun [transformAndRender](../-abstract-element/transform-and-render.html)(drawContext: DrawContext, tickDelta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Transforms and renders the element. |

