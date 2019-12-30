[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.model](../index.md) / [ITimeRange](./index.md)

# ITimeRange

`interface ITimeRange`

### Functions

| Name | Summary |
|---|---|
| [getEndTimeInSecs](get-end-time-in-secs.md) | `abstract fun getEndTimeInSecs(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getStartTimeInSecs](get-start-time-in-secs.md) | `abstract fun getStartTimeInSecs(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [setEndTimeInSecs](set-end-time-in-secs.md) | `abstract fun setEndTimeInSecs(endTimeInSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStartTimeInSecs](set-start-time-in-secs.md) | `abstract fun setStartTimeInSecs(startTimeInSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [EventTrackItem](../../com.skedgo.tripkit.common.agenda/-event-track-item/index.md) | `open class EventTrackItem : `[`TrackItem`](../../com.skedgo.tripkit.common.agenda/-track-item/index.md)`, `[`ITimeRange`](./index.md) |
| [TimetableEntry](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md) | (Aka Service)`open class TimetableEntry : Parcelable, `[`IRealTimeElement`](../../com.skedgo.tripkit.common.agenda/-i-real-time-element/index.md)`, `[`ITimeRange`](./index.md)`, `[`WheelchairAccessible`](../-wheelchair-accessible/index.md) |
| [Trip](../../com.skedgo.tripkit.routing/-trip/index.md) | A ``[`Trip`](../../com.skedgo.tripkit.routing/-trip/index.md) will mainly hold a list of ``[`TripSegment`](../../com.skedgo.tripkit.routing/-trip-segment/index.md)s which denotes how to go from ``[`Trip#getFrom()`](../../com.skedgo.tripkit.routing/-trip/get-from.md) to ``[`Trip#getTo()`](../../com.skedgo.tripkit.routing/-trip/get-to.md). `open class Trip : `[`ITimeRange`](./index.md) |
| [TripSegment](../../com.skedgo.tripkit.routing/-trip-segment/index.md) | To go from A to B, sometimes we have to travel X, Y, Z locations between A and B. That means, we travel A to X, then X to Y, then Y to Z, then Z to B which is the destination. To show how to travel from A to X, we use ``[`TripSegment`](../../com.skedgo.tripkit.routing/-trip-segment/index.md). So, in this case, a trip from A to B comprises 6 segments: - A segment whose type is ``[`SegmentType#DEPARTURE`](../../com.skedgo.tripkit.routing/-segment-type/-d-e-p-a-r-t-u-r-e.md). - A segment from A to X. - A segment from X to Y. - A segment from Y to Z. - A segment from Z to B. - A segment whose type is ``[`SegmentType#ARRIVAL`](../../com.skedgo.tripkit.routing/-segment-type/-a-r-r-i-v-a-l.md). `open class TripSegment : `[`IRealTimeElement`](../../com.skedgo.tripkit.common.agenda/-i-real-time-element/index.md)`, `[`ITimeRange`](./index.md) |
