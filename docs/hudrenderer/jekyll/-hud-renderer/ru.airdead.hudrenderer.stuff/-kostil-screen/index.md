---
title: KostilScreen
---
//[HudRenderer](../../../index.html)/[ru.airdead.hudrenderer.stuff](../index.html)/[KostilScreen](index.html)



# KostilScreen



[jvm]\
class [KostilScreen](index.html) : Screen

Custom screen class used to handle context menus. Inherits from Screen.



## Constructors


| | |
|---|---|
| [KostilScreen](-kostil-screen.html) | [jvm]<br>constructor() |


## Properties


| Name | Summary |
|---|---|
| [dragging](index.html#1631288554%2FProperties%2F863300109) | [jvm]<br>var [dragging](index.html#1631288554%2FProperties%2F863300109): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [focused](index.html#86460682%2FProperties%2F863300109) | [jvm]<br>@Nullable<br>@get:Nullable<br>var [focused](index.html#86460682%2FProperties%2F863300109): Element? |
| [height](index.html#-1391382990%2FProperties%2F863300109) | [jvm]<br>var [height](index.html#-1391382990%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [width](index.html#826009467%2FProperties%2F863300109) | [jvm]<br>var [width](index.html#826009467%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Functions


| Name | Summary |
|---|---|
| [applyKeyPressNarratorDelay](index.html#-1467076079%2FFunctions%2F863300109) | [jvm]<br>open fun [applyKeyPressNarratorDelay](index.html#-1467076079%2FFunctions%2F863300109)() |
| [applyMouseMoveNarratorDelay](index.html#-412686033%2FFunctions%2F863300109) | [jvm]<br>open fun [applyMouseMoveNarratorDelay](index.html#-412686033%2FFunctions%2F863300109)() |
| [applyMousePressScrollNarratorDelay](index.html#-1903663944%2FFunctions%2F863300109) | [jvm]<br>open fun [applyMousePressScrollNarratorDelay](index.html#-1903663944%2FFunctions%2F863300109)() |
| [applyNarratorModeChangeDelay](index.html#277180960%2FFunctions%2F863300109) | [jvm]<br>open fun [applyNarratorModeChangeDelay](index.html#277180960%2FFunctions%2F863300109)() |
| [charTyped](index.html#1099199689%2FFunctions%2F863300109) | [jvm]<br>open override fun [charTyped](index.html#1099199689%2FFunctions%2F863300109)(chr: [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html), modifiers: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [children](index.html#-854751910%2FFunctions%2F863300109) | [jvm]<br>open override fun [children](index.html#-854751910%2FFunctions%2F863300109)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;out Element&gt; |
| [close](index.html#-1177783415%2FFunctions%2F863300109) | [jvm]<br>open fun [close](index.html#-1177783415%2FFunctions%2F863300109)() |
| [filesDragged](index.html#-2134224977%2FFunctions%2F863300109) | [jvm]<br>open fun [filesDragged](index.html#-2134224977%2FFunctions%2F863300109)(paths: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Path](https://docs.oracle.com/javase/8/docs/api/java/nio/file/Path.html)&gt;) |
| [focusOn](index.html#1588365331%2FFunctions%2F863300109) | [jvm]<br>open fun [focusOn](index.html#1588365331%2FFunctions%2F863300109)(@Nullableelement: Element?) |
| [getFocusedPath](index.html#-454564843%2FFunctions%2F863300109) | [jvm]<br>@Nullable<br>open override fun [getFocusedPath](index.html#-454564843%2FFunctions%2F863300109)(): GuiNavigationPath? |
| [getMusic](index.html#2097179882%2FFunctions%2F863300109) | [jvm]<br>@Nullable<br>open fun [getMusic](index.html#2097179882%2FFunctions%2F863300109)(): MusicSound? |
| [getNarratedTitle](index.html#1163058492%2FFunctions%2F863300109) | [jvm]<br>open fun [getNarratedTitle](index.html#1163058492%2FFunctions%2F863300109)(): Text |
| [getNavigationFocus](index.html#-1864553909%2FFunctions%2F863300109) | [jvm]<br>open override fun [getNavigationFocus](index.html#-1864553909%2FFunctions%2F863300109)(): ScreenRect |
| [getNavigationOrder](index.html#457112462%2FFunctions%2F863300109) | [jvm]<br>open fun [getNavigationOrder](index.html#457112462%2FFunctions%2F863300109)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNavigationPath](index.html#1852707961%2FFunctions%2F863300109) | [jvm]<br>@Nullable<br>open override fun [getNavigationPath](index.html#1852707961%2FFunctions%2F863300109)(navigation: GuiNavigation): GuiNavigationPath? |
| [getTitle](index.html#846284823%2FFunctions%2F863300109) | [jvm]<br>open fun [getTitle](index.html#846284823%2FFunctions%2F863300109)(): Text |
| [handleContextMenus](handle-context-menus.html) | [jvm]<br>inline fun [handleContextMenus](handle-context-menus.html)(action: ([ContextMenu](../../ru.airdead.hudrenderer.element/-context-menu/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Handles actions on context menus. |
| [handleTextClick](index.html#-1273299977%2FFunctions%2F863300109) | [jvm]<br>open fun [handleTextClick](index.html#-1273299977%2FFunctions%2F863300109)(@Nullablestyle: Style?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hoveredElement](index.html#226213711%2FFunctions%2F863300109) | [jvm]<br>open fun [hoveredElement](index.html#226213711%2FFunctions%2F863300109)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)&lt;Element&gt; |
| [init](index.html#1514544322%2FFunctions%2F863300109) | [jvm]<br>fun [init](index.html#1514544322%2FFunctions%2F863300109)(client: MinecraftClient, width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [isFocused](index.html#568890898%2FFunctions%2F863300109) | [jvm]<br>open override fun [isFocused](index.html#568890898%2FFunctions%2F863300109)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isMouseOver](index.html#-93925673%2FFunctions%2F863300109) | [jvm]<br>open override fun [isMouseOver](index.html#-93925673%2FFunctions%2F863300109)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [keyPressed](key-pressed.html) | [jvm]<br>open override fun [keyPressed](key-pressed.html)(keyCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), scanCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), modifiers: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Handles key press events. |
| [keyReleased](index.html#1203276193%2FFunctions%2F863300109) | [jvm]<br>open override fun [keyReleased](index.html#1203276193%2FFunctions%2F863300109)(keyCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), scanCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), modifiers: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [mouseClicked](index.html#784073197%2FFunctions%2F863300109) | [jvm]<br>open override fun [mouseClicked](index.html#784073197%2FFunctions%2F863300109)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), button: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [mouseDragged](mouse-dragged.html) | [jvm]<br>open override fun [mouseDragged](mouse-dragged.html)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), button: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), deltaX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), deltaY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Handles mouse drag events. |
| [mouseMoved](index.html#-1173613646%2FFunctions%2F863300109) | [jvm]<br>open fun [mouseMoved](index.html#-1173613646%2FFunctions%2F863300109)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [mouseReleased](index.html#1447314737%2FFunctions%2F863300109) | [jvm]<br>open override fun [mouseReleased](index.html#1447314737%2FFunctions%2F863300109)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), button: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [mouseScrolled](mouse-scrolled.html) | [jvm]<br>open override fun [mouseScrolled](mouse-scrolled.html)(mouseX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), mouseY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), amount: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Handles mouse scroll events. |
| [narrateScreenIfNarrationEnabled](index.html#-451757697%2FFunctions%2F863300109) | [jvm]<br>open fun [narrateScreenIfNarrationEnabled](index.html#-451757697%2FFunctions%2F863300109)(onlyChangedNarrations: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [onDisplayed](index.html#123137023%2FFunctions%2F863300109) | [jvm]<br>open fun [onDisplayed](index.html#123137023%2FFunctions%2F863300109)() |
| [removed](index.html#-1518953183%2FFunctions%2F863300109) | [jvm]<br>open fun [removed](index.html#-1518953183%2FFunctions%2F863300109)() |
| [render](index.html#841400148%2FFunctions%2F863300109) | [jvm]<br>open override fun [render](index.html#841400148%2FFunctions%2F863300109)(context: DrawContext, mouseX: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mouseY: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), delta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [renderBackground](index.html#1348362958%2FFunctions%2F863300109) | [jvm]<br>open fun [renderBackground](index.html#1348362958%2FFunctions%2F863300109)(context: DrawContext) |
| [renderBackgroundTexture](index.html#821296387%2FFunctions%2F863300109) | [jvm]<br>open fun [renderBackgroundTexture](index.html#821296387%2FFunctions%2F863300109)(context: DrawContext) |
| [renderWithTooltip](index.html#-316300643%2FFunctions%2F863300109) | [jvm]<br>fun [renderWithTooltip](index.html#-316300643%2FFunctions%2F863300109)(context: DrawContext, mouseX: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mouseY: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), delta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [resize](index.html#822377374%2FFunctions%2F863300109) | [jvm]<br>open fun [resize](index.html#822377374%2FFunctions%2F863300109)(client: MinecraftClient, width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setFocused](index.html#-6075125%2FFunctions%2F863300109) | [jvm]<br>open override fun [setFocused](index.html#-6075125%2FFunctions%2F863300109)(focused: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setTooltip](index.html#-464690589%2FFunctions%2F863300109) | [jvm]<br>open fun [setTooltip](index.html#-464690589%2FFunctions%2F863300109)(tooltip: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;OrderedText&gt;)<br>open fun [setTooltip](index.html#184729010%2FFunctions%2F863300109)(tooltip: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;OrderedText&gt;, positioner: TooltipPositioner, focused: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>open fun [setTooltip](index.html#-1964272461%2FFunctions%2F863300109)(tooltip: Tooltip, positioner: TooltipPositioner, focused: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [shouldCloseOnEsc](should-close-on-esc.html) | [jvm]<br>open override fun [shouldCloseOnEsc](should-close-on-esc.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Determines whether the screen should close when the escape key is pressed. |
| [shouldPause](index.html#865618142%2FFunctions%2F863300109) | [jvm]<br>open fun [shouldPause](index.html#865618142%2FFunctions%2F863300109)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [tick](index.html#1100545404%2FFunctions%2F863300109) | [jvm]<br>open fun [tick](index.html#1100545404%2FFunctions%2F863300109)() |
| [updateNarrator](index.html#-1848867129%2FFunctions%2F863300109) | [jvm]<br>open fun [updateNarrator](index.html#-1848867129%2FFunctions%2F863300109)() |

