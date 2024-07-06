---
title: Parent
---
//[HudRenderer](../../../index.html)/[ru.airdead.hudrenderer.element](../index.html)/[Parent](index.html)



# Parent

interface [Parent](index.html) : [IElement](../-i-element/index.html)

Interface representing a parent element in the UI. Inherits from [IElement](../-i-element/index.html).



#### Inheritors


| |
|---|
| [BeautifulRectangleElement](../-beautiful-rectangle-element/index.html) |
| [ContextMenu](../-context-menu/index.html) |
| [RectangleElement](../-rectangle-element/index.html) |


## Properties


| Name | Summary |
|---|---|
| [children](children.html) | [jvm]<br>abstract val [children](children.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[AbstractElement](../-abstract-element/index.html)&gt;<br>The list of child elements. |
| [size](../-i-element/size.html) | [jvm]<br>abstract val [size](../-i-element/size.html): [V3](../../ru.airdead.hudrenderer.utility/-v3/index.html) |


## Functions


| Name | Summary |
|---|---|
| [addChild](add-child.html) | [jvm]<br>open fun [addChild](add-child.html)(vararg elements: [AbstractElement](../-abstract-element/index.html))<br>Adds multiple child elements to the parent.<br>[jvm]<br>open fun [addChild](add-child.html)(element: [AbstractElement](../-abstract-element/index.html))<br>Adds a child element to the parent. |
| [plus](plus.html) | [jvm]<br>open operator fun &lt;[T](plus.html) : [AbstractElement](../-abstract-element/index.html)&gt; [plus](plus.html)(element: [T](plus.html)): [T](plus.html)<br>Adds a child element to the parent using the plus operator. |
| [removeChild](remove-child.html) | [jvm]<br>open fun [removeChild](remove-child.html)(vararg elements: [AbstractElement](../-abstract-element/index.html))<br>Removes multiple child elements from the parent.<br>[jvm]<br>open fun [removeChild](remove-child.html)(element: [AbstractElement](../-abstract-element/index.html))<br>Removes a child element from the parent. |
| [unaryPlus](unary-plus.html) | [jvm]<br>open operator fun &lt;[T](unary-plus.html) : [AbstractElement](../-abstract-element/index.html)&gt; [T](unary-plus.html).[unaryPlus](unary-plus.html)(): [T](unary-plus.html)<br>Adds a child element to the parent using the unary plus operator. |

