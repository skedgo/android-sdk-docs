[tripkit-android](../../index.md) / [com.skedgo.android.common.util](../index.md) / [TripSegmentListResolver](./index.md)

# TripSegmentListResolver

`open class TripSegmentListResolver`

Puts a Departure segment before head of, and puts an Arrival segment after tail of a segment list.

 Also, fills identifiers for segments.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TripSegmentListResolver(resources: Resources!)` |

### Functions

| Name | Summary |
|---|---|
| [createArrivalSegment](create-arrival-segment.md) | Creates the Arrival segment from the last segment`open fun createArrivalSegment(lastSegment: `[`TripSegment`](../../skedgo.tripkit.routing/-trip-segment/index.md)`!): `[`TripSegment`](../../skedgo.tripkit.routing/-trip-segment/index.md)`!` |
| [createDepartureSegment](create-departure-segment.md) | Creates the Departure segment from the first segment`open fun createDepartureSegment(firstSegment: `[`TripSegment`](../../skedgo.tripkit.routing/-trip-segment/index.md)`!): `[`TripSegment`](../../skedgo.tripkit.routing/-trip-segment/index.md)`!` |
| [resolve](resolve.md) | `open fun resolve(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setDestination](set-destination.md) | `open fun setDestination(destination: `[`Location`](../../com.skedgo.android.common.model/-location/index.md)`!): `[`TripSegmentListResolver`](./index.md)`!` |
| [setOrigin](set-origin.md) | `open fun setOrigin(origin: `[`Location`](../../com.skedgo.android.common.model/-location/index.md)`!): `[`TripSegmentListResolver`](./index.md)`!` |
| [setTripSegmentList](set-trip-segment-list.md) | `open fun setTripSegmentList(tripSegmentList: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripSegment`](../../skedgo.tripkit.routing/-trip-segment/index.md)`!>!): `[`TripSegmentListResolver`](./index.md)`!` |
