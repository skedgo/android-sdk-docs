[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.routeinput](../index.md) / [RouteInputView](./index.md)

# RouteInputView

`class RouteInputView : CardView, OnClickListener`

A widget for display start and destination locations, as well as departure/arrival times and a "Route" button.

### Types

| Name | Summary |
|---|---|
| [OnRouteWidgetClickedListener](-on-route-widget-clicked-listener/index.md) | Interface definition for a callback that is called when one of several widgets are clicked.`interface OnRouteWidgetClickedListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RouteInputView(context: Context)`<br>`RouteInputView(context: Context, attrs: AttributeSet?)` |

### Properties

| Name | Summary |
|---|---|
| [viewModel](view-model.md) | `lateinit var viewModel: `[`RouteInputViewModel`](../-route-input-view-model/index.md) |

### Functions

| Name | Summary |
|---|---|
| [onClick](on-click.md) | `fun onClick(view: View?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setDestinationText](set-destination-text.md) | Sets the displayed text in the Destination field.`fun setDestinationText(text: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOnRouteWidgetClickedListener](set-on-route-widget-clicked-listener.md) | Register a callback to be invoked when a widget is clicked.`fun setOnRouteWidgetClickedListener(callback: OnRouteWidgetClickedListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`fun setOnRouteWidgetClickedListener(listener: (Widget) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStartText](set-start-text.md) | Sets the displayed text in the Start field.`fun setStartText(text: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTimeButton](set-time-button.md) | Sets the displayed text on the Time button.`fun setTimeButton(text: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
