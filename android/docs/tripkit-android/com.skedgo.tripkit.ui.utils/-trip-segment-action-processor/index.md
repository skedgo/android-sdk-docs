[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.utils](../index.md) / [TripSegmentActionProcessor](./index.md)

# TripSegmentActionProcessor

`class TripSegmentActionProcessor`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TripSegmentActionProcessor()` |

### Properties

| Name | Summary |
|---|---|
| [directionRegex](direction-regex.md) | `val directionRegex: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) |
| [doubleSpaceReplace](double-space-replace.md) | `val doubleSpaceReplace: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) |
| [durationRegex](duration-regex.md) | `val durationRegex: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) |
| [emptyRemoveRegex](empty-remove-regex.md) | `val emptyRemoveRegex: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) |
| [lineNameRegex](line-name-regex.md) | `val lineNameRegex: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) |
| [locationsRegex](locations-regex.md) | `val locationsRegex: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) |
| [numberRegex](number-regex.md) | `val numberRegex: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) |
| [platformRegex](platform-regex.md) | `val platformRegex: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) |
| [singleDotReplace](single-dot-replace.md) | `val singleDotReplace: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) |
| [stopsRegex](stops-regex.md) | `val stopsRegex: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) |
| [timeRegex](time-regex.md) | `val timeRegex: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) |
| [trafficRegex](traffic-regex.md) | `val trafficRegex: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html) |

### Functions

| Name | Summary |
|---|---|
| [hasTime](has-time.md) | `fun hasTime(segment: `[`TripSegment`](../../com.skedgo.tripkit.routing/-trip-segment/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [processText](process-text.md) | `fun processText(context: Context, segment: `[`TripSegment`](../../com.skedgo.tripkit.routing/-trip-segment/index.md)`, text: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, withTime: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
