---
title: Color
---
//[HudRenderer](../../../index.html)/[ru.airdead.hudrenderer.utility](../index.html)/[Color](index.html)



# Color



[jvm]\
open class [Color](index.html)(var red: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, var green: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, var blue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, var alpha: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0)

Class representing a color with red, green, blue, and alpha (transparency) components.



## Constructors


| | |
|---|---|
| [Color](-color.html) | [jvm]<br>constructor(red: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, green: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, blue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, alpha: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0) |


## Properties


| Name | Summary |
|---|---|
| [alpha](alpha.html) | [jvm]<br>open var [alpha](alpha.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The alpha component of the color (0.0-1.0). |
| [blue](blue.html) | [jvm]<br>open var [blue](blue.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The blue component of the color (0-255). |
| [green](green.html) | [jvm]<br>open var [green](green.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The green component of the color (0-255). |
| [red](red.html) | [jvm]<br>open var [red](red.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The red component of the color (0-255). |


## Functions


| Name | Summary |
|---|---|
| [copy](copy.html) | [jvm]<br>fun [copy](copy.html)(): [Color](index.html)<br>Creates a copy of the color instance. |
| [toInt](to-int.html) | [jvm]<br>fun [toInt](to-int.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Converts the color to an integer representation. |
| [write](write.html) | [jvm]<br>open fun [write](write.html)(another: [Color](index.html))<br>Writes the values of this color to another color instance. |

