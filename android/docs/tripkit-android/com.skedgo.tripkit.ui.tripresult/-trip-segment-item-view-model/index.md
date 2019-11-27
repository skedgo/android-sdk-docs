[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresult](../index.md) / [TripSegmentItemViewModel](./index.md)

# TripSegmentItemViewModel

`class TripSegmentItemViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Types

| Name | Summary |
|---|---|
| [SegmentViewType](-segment-view-type/index.md) | `enum class SegmentViewType` |

### Properties

| Name | Summary |
|---|---|
| [backgroundCircleTint](background-circle-tint.md) | `val backgroundCircleTint: ObservableField<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [bottomLineTint](bottom-line-tint.md) | `val bottomLineTint: ObservableField<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [description](description.md) | `val description: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [endTime](end-time.md) | `val endTime: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [icon](icon.md) | `val icon: ObservableField<Drawable>` |
| [showBackgroundCircle](show-background-circle.md) | `val showBackgroundCircle: ObservableBoolean` |
| [showBottomLine](show-bottom-line.md) | `val showBottomLine: ObservableBoolean` |
| [showDescription](show-description.md) | `val showDescription: ObservableBoolean` |
| [showEndTime](show-end-time.md) | `val showEndTime: ObservableBoolean` |
| [showStartTime](show-start-time.md) | `val showStartTime: ObservableBoolean` |
| [showTopLine](show-top-line.md) | `val showTopLine: ObservableBoolean` |
| [startTime](start-time.md) | `val startTime: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [title](title.md) | `val title: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [topLineTint](top-line-tint.md) | `val topLineTint: ObservableField<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [tripSegment](trip-segment.md) | `var tripSegment: `[`TripSegment`](../../skedgo.tripkit.routing/-trip-segment/index.md)`?` |

### Functions

| Name | Summary |
|---|---|
| [setupSegment](setup-segment.md) | `fun setupSegment(viewType: SegmentViewType, title: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, startTime: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, endTime: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, lineColor: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = Color.TRANSPARENT, topConnectionColor: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = lineColor, bottomConnectionColor: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = lineColor): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [showSegmentIcon](show-segment-icon.md) | `fun showSegmentIcon(segment: `[`TripSegment`](../../skedgo.tripkit.routing/-trip-segment/index.md)`, tintWhite: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
