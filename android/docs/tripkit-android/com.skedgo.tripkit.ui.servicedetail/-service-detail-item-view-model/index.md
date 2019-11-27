[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.servicedetail](../index.md) / [ServiceDetailItemViewModel](./index.md)

# ServiceDetailItemViewModel

`class ServiceDetailItemViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Types

| Name | Summary |
|---|---|
| [LineDirection](-line-direction/index.md) | `enum class LineDirection` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServiceDetailItemViewModel(getStopTimeDisplayText: `[`GetStopTimeDisplayText`](../-get-stop-time-display-text/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [getStopTimeDisplayText](get-stop-time-display-text.md) | `val getStopTimeDisplayText: `[`GetStopTimeDisplayText`](../-get-stop-time-display-text/index.md) |
| [lineColor](line-color.md) | `var lineColor: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [lineDrawable](line-drawable.md) | `val lineDrawable: ObservableField<NinePatchDrawable>` |
| [onItemClick](on-item-click.md) | `val onItemClick: `[`TapAction`](../../com.skedgo.tripkit.ui.utils/-tap-action/index.md)`<`[`StopInfo`](../../com.skedgo.tripkit.ui.model/-stop-info/index.md)`?>` |
| [scheduledTime](scheduled-time.md) | `val scheduledTime: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [scheduledTimeTextColor](scheduled-time-text-color.md) | `val scheduledTimeTextColor: ObservableInt` |
| [stop](stop.md) | `var stop: `[`StopInfo`](../../com.skedgo.tripkit.ui.model/-stop-info/index.md)`?` |
| [stopName](stop-name.md) | `val stopName: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [stopNameColor](stop-name-color.md) | `val stopNameColor: ObservableInt` |

### Functions

| Name | Summary |
|---|---|
| [setDrawable](set-drawable.md) | `fun setDrawable(context: Context, direction: LineDirection): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStop](set-stop.md) | `fun setStop(context: Context, stop: `[`StopInfo`](../../com.skedgo.tripkit.ui.model/-stop-info/index.md)`, _lineColor: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, travelled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
