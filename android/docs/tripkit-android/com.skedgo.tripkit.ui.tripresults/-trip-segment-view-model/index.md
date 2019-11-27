[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresults](../index.md) / [TripSegmentViewModel](./index.md)

# TripSegmentViewModel

`class TripSegmentViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TripSegmentViewModel(context: Context, printTime: `[`PrintTime`](../../skedgo.tripkit.datetime/-print-time/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [getTransportIconTintStrategy](get-transport-icon-tint-strategy.md) | `lateinit var getTransportIconTintStrategy: `[`GetTransportIconTintStrategy`](../-get-transport-icon-tint-strategy/index.md) |
| [icon](icon.md) | `val icon: ObservableField<Drawable>` |
| [primaryText](primary-text.md) | `val primaryText: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [secondaryText](secondary-text.md) | `val secondaryText: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [showPrimary](show-primary.md) | `val showPrimary: ObservableBoolean` |
| [showSecondary](show-secondary.md) | `val showSecondary: ObservableBoolean` |

### Functions

| Name | Summary |
|---|---|
| [setSegment](set-segment.md) | `fun setSegment(trip: `[`Trip`](../../skedgo.tripkit.routing/-trip/index.md)`, segment: `[`TripSegment`](../../skedgo.tripkit.routing/-trip-segment/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
