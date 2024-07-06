---
title: HudManager
---
//[HudRenderer](../../../index.html)/[ru.airdead.hudrenderer](../index.html)/[HudManager](index.html)



# HudManager



[jvm]\
object [HudManager](index.html)

Singleton object managing UI elements.



## Functions


| Name | Summary |
|---|---|
| [addElement](add-element.html) | [jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)<br>fun [addElement](add-element.html)(element: [AbstractElement](../../ru.airdead.hudrenderer.element/-abstract-element/index.html))<br>Adds an element to the UI manager. |
| [elements](elements.html) | [jvm]<br>fun [elements](elements.html)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[AbstractElement](../../ru.airdead.hudrenderer.element/-abstract-element/index.html)&gt;<br>Returns the list of all UI elements. |
| [removeElement](remove-element.html) | [jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)<br>fun [removeElement](remove-element.html)(element: [AbstractElement](../../ru.airdead.hudrenderer.element/-abstract-element/index.html))<br>Removes an element from the UI manager. |
| [render](render.html) | [jvm]<br>fun [render](render.html)(drawContext: DrawContext, tickDelta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Renders all UI elements. |
| [update](update.html) | [jvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)<br>fun [update](update.html)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), isLeftTurn: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), isRightTurn: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Updates the state of the UI elements based on mouse input. |

