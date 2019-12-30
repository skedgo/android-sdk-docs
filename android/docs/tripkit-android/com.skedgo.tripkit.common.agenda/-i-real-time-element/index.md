[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.agenda](../index.md) / [IRealTimeElement](./index.md)

# IRealTimeElement

`interface IRealTimeElement`

Signifies a class is able to fetch timetable information

### Functions

| Name | Summary |
|---|---|
| [getEndStopCode](get-end-stop-code.md) | `abstract fun getEndStopCode(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getOperator](get-operator.md) | `abstract fun getOperator(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getServiceTripId](get-service-trip-id.md) | `abstract fun getServiceTripId(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getStartStopCode](get-start-stop-code.md) | `abstract fun getStartStopCode(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getStartTimeInSecs](get-start-time-in-secs.md) | `abstract fun getStartTimeInSecs(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [setEndStopCode](set-end-stop-code.md) | `abstract fun setEndStopCode(endStopCode: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStartStopCode](set-start-stop-code.md) | `abstract fun setStartStopCode(startStopCode: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [TimetableEntry](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md) | (Aka Service)`open class TimetableEntry : Parcelable, `[`IRealTimeElement`](./index.md)`, `[`ITimeRange`](../../com.skedgo.tripkit.common.model/-i-time-range/index.md)`, `[`WheelchairAccessible`](../../com.skedgo.tripkit.common.model/-wheelchair-accessible/index.md) |
| [TripSegment](../../com.skedgo.tripkit.routing/-trip-segment/index.md) | To go from A to B, sometimes we have to travel X, Y, Z locations between A and B. That means, we travel A to X, then X to Y, then Y to Z, then Z to B which is the destination. To show how to travel from A to X, we use ``[`TripSegment`](../../com.skedgo.tripkit.routing/-trip-segment/index.md). So, in this case, a trip from A to B comprises 6 segments: - A segment whose type is ``[`SegmentType#DEPARTURE`](../../com.skedgo.tripkit.routing/-segment-type/-d-e-p-a-r-t-u-r-e.md). - A segment from A to X. - A segment from X to Y. - A segment from Y to Z. - A segment from Z to B. - A segment whose type is ``[`SegmentType#ARRIVAL`](../../com.skedgo.tripkit.routing/-segment-type/-a-r-r-i-v-a-l.md). `open class TripSegment : `[`IRealTimeElement`](./index.md)`, `[`ITimeRange`](../../com.skedgo.tripkit.common.model/-i-time-range/index.md) |
