[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresults](../index.md) / [TripResultViewModel](./index.md)

# TripResultViewModel

`class TripResultViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TripResultViewModel(context: Context, tripSegmentHelper: `[`TripSegmentHelper`](../-trip-segment-helper/index.md)`, printTime: `[`PrintTime`](../../com.skedgo.tripkit.datetime/-print-time/index.md)`, resources: Resources)` |

### Properties

| Name | Summary |
|---|---|
| [alternateSegments](alternate-segments.md) | `val alternateSegments: `[`ArrayList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)`<`[`TripSegmentViewModel`](../-trip-segment-view-model/index.md)`>` |
| [alternateSubtitle](alternate-subtitle.md) | `val alternateSubtitle: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [alternateTitle](alternate-title.md) | `val alternateTitle: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [alternateTitleVisible](alternate-title-visible.md) | `val alternateTitleVisible: ObservableBoolean` |
| [alternateTripVisible](alternate-trip-visible.md) | `val alternateTripVisible: ObservableBoolean` |
| [badgeDrawable](badge-drawable.md) | `val badgeDrawable: ObservableField<Drawable>` |
| [badgeText](badge-text.md) | `val badgeText: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [badgeTextColor](badge-text-color.md) | `val badgeTextColor: ObservableInt` |
| [badgeVisible](badge-visible.md) | `val badgeVisible: ObservableBoolean` |
| [cost](cost.md) | `val cost: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [costVisible](cost-visible.md) | `val costVisible: ObservableBoolean` |
| [group](group.md) | `lateinit var group: `[`TripGroup`](../../com.skedgo.tripkit.routing/-trip-group/index.md) |
| [moreButtonText](more-button-text.md) | `val moreButtonText: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [moreButtonVisible](more-button-visible.md) | `val moreButtonVisible: ObservableBoolean` |
| [onItemClicked](on-item-clicked.md) | `val onItemClicked: `[`TapAction`](../../com.skedgo.tripkit.ui.utils/-tap-action/index.md)`<`[`TripResultViewModel`](./index.md)`>` |
| [onMoreButtonClicked](on-more-button-clicked.md) | `val onMoreButtonClicked: `[`TapAction`](../../com.skedgo.tripkit.ui.utils/-tap-action/index.md)`<`[`TripResultViewModel`](./index.md)`>` |
| [otherTripGroups](other-trip-groups.md) | `var otherTripGroups: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Trip`](../../com.skedgo.tripkit.routing/-trip/index.md)`>?` |
| [segments](segments.md) | `val segments: `[`ArrayList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)`<`[`TripSegmentViewModel`](../-trip-segment-view-model/index.md)`>` |
| [subtitle](subtitle.md) | `val subtitle: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [title](title.md) | `val title: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [titleVisible](title-visible.md) | `val titleVisible: ObservableBoolean` |
| [trip](trip.md) | `lateinit var trip: `[`Trip`](../../com.skedgo.tripkit.routing/-trip/index.md) |

### Functions

| Name | Summary |
|---|---|
| [moreButtonClicked](more-button-clicked.md) | `fun moreButtonClicked(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTripGroup](set-trip-group.md) | `fun setTripGroup(context: Context, tripgroup: `[`TripGroup`](../../com.skedgo.tripkit.routing/-trip-group/index.md)`, classification: Classification): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
