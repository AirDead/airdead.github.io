---
title: AbstractElement
---
//[HudRenderer](../../../index.html)/[ru.airdead.hudrenderer.element](../index.html)/[AbstractElement](index.html)



# AbstractElement

abstract class [AbstractElement](index.html) : [IElement](../-i-element/index.html)

Abstract base class representing a UI element in the UIEngine. Implements the [IElement](../-i-element/index.html) interface.



#### Inheritors


| |
|---|
| [BeautifulRectangleElement](../-beautiful-rectangle-element/index.html) |
| [ContextMenu](../-context-menu/index.html) |
| [RectangleElement](../-rectangle-element/index.html) |
| [TextElement](../-text-element/index.html) |


## Constructors


| | |
|---|---|
| [AbstractElement](-abstract-element.html) | [jvm]<br>constructor() |


## Properties


| Name | Summary |
|---|---|
| [align](align.html) | [jvm]<br>var [align](align.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The alignment of this element. |
| [color](color.html) | [jvm]<br>open var [color](color.html): [Color](../../ru.airdead.hudrenderer.utility/-color/index.html)<br>The color of this element. |
| [enabled](enabled.html) | [jvm]<br>open var [enabled](enabled.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates whether the element is enabled. If disabled, the element will not be interactable. |
| [interactable](interactable.html) | [jvm]<br>open var [interactable](interactable.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Indicates whether the element is interactable. If the element is disabled, it cannot be interactable. |
| [lastParent](last-parent.html) | [jvm]<br>var [lastParent](last-parent.html): [AbstractElement](index.html)?<br>The last parent element of this element. |
| [offset](offset.html) | [jvm]<br>var [offset](offset.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The offset of this element from its original position. |
| [origin](origin.html) | [jvm]<br>var [origin](origin.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The origin point of this element. |
| [renderLocation](render-location.html) | [jvm]<br>var [renderLocation](render-location.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The render location of this element in 3D space. |
| [rotation](rotation.html) | [jvm]<br>var [rotation](rotation.html): [Rotation](../../ru.airdead.hudrenderer.utility/-rotation/index.html)<br>The rotation of this element. |
| [size](size.html) | [jvm]<br>open override var [size](size.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html)<br>The size of this element. |


## Functions


| Name | Summary |
|---|---|
| [handleMouseClick](handle-mouse-click.html) | [jvm]<br>open fun [handleMouseClick](handle-mouse-click.html)(button: [MouseButton](../../ru.airdead.hudrenderer.utility/-mouse-button/index.html), pressed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Handles mouse click events. |
| [handleMouseHover](handle-mouse-hover.html) | [jvm]<br>open fun [handleMouseHover](handle-mouse-hover.html)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Handles mouse hover events. |
| [isHovered](is-hovered.html) | [jvm]<br>fun [isHovered](is-hovered.html)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the element is hovered based on the mouse coordinates. |
| [onClick](on-click.html) | [jvm]<br>fun [onClick](on-click.html)(handler: [ClickHandler](../../ru.airdead.hudrenderer.utility/-click-handler/index.html))<br>Sets a handler for click events. |
| [onHover](on-hover.html) | [jvm]<br>fun [onHover](on-hover.html)(handler: [HoverHandler](../../ru.airdead.hudrenderer.utility/-hover-handler/index.html))<br>Sets a handler for hover events. |
| [render](render.html) | [jvm]<br>abstract fun [render](render.html)(drawContext: DrawContext, tickDelta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Renders the element. Must be implemented by subclasses. |
| [transformAndRender](transform-and-render.html) | [jvm]<br>fun [transformAndRender](transform-and-render.html)(drawContext: DrawContext, tickDelta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Transforms and renders the element. |

