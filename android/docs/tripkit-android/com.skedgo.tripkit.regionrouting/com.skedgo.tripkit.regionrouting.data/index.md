[tripkit-android](../index.md) / [com.skedgo.tripkit.routing](./index.md)

## Package com.skedgo.tripkit.routing

### Types

| Name | Summary |
|---|---|
| [Availability](-availability/index.md) | `enum class Availability` |
| [ExtraQueryMapProvider](-extra-query-map-provider/index.md) | A decorator that puts additional query params into the query map that is supplied into ``[`A2bRoutingApi`](../com.skedgo.tripkit.a2brouting/-a2b-routing-api/index.md). Note that you should only use this when you really do know what you intend to do.`interface ExtraQueryMapProvider` |
| [GroupVisibility](-group-visibility/index.md) | `class GroupVisibility` |
| [LocalCost](-local-cost/index.md) | `abstract class LocalCost : Parcelable` |
| [LocalCostAccuracy](-local-cost-accuracy/index.md) | `enum class LocalCostAccuracy` |
| [ModeInfo](-mode-info/index.md) | `open class ModeInfo : Parcelable` |
| [Occupancy](-occupancy/index.md) | `enum class Occupancy` |
| [Provider](-provider/index.md) | `abstract class Provider : Parcelable` |
| [RealTimeVehicle](-real-time-vehicle/index.md) | `open class RealTimeVehicle : Parcelable` |
| [RoutingResponse](-routing-response/index.md) | `open class RoutingResponse` |
| [SegmentActionTemplates](-segment-action-templates/index.md) | `class SegmentActionTemplates` |
| [SegmentJsonKeys](-segment-json-keys/index.md) | `class SegmentJsonKeys` |
| [SegmentNotesTemplates](-segment-notes-templates/index.md) | `class SegmentNotesTemplates` |
| [SegmentType](-segment-type/index.md) | `enum class SegmentType` |
| [ServiceColor](-service-color/index.md) | `class ServiceColor : Parcelable` |
| [Shape](-shape/index.md) | `open class Shape : Parcelable` |
| [Source](-source/index.md) | `abstract class Source : Parcelable` |
| [Templates](-templates/index.md) | `class Templates` |
| [Trip](-trip/index.md) | A ``[`Trip`](-trip/index.md) will mainly hold a list of ``[`TripSegment`](-trip-segment/index.md)s which denotes how to go from ``[`Trip#getFrom()`](-trip/get-from.md) to ``[`Trip#getTo()`](-trip/get-to.md). `open class Trip : `[`ITimeRange`](../com.skedgo.tripkit.common.model/-i-time-range/index.md) |
| [TripComparators](-trip-comparators/index.md) | `class TripComparators` |
| [TripGroup](-trip-group/index.md) | Represents a list of ``[`Trip`](-trip/index.md)s. A list of ``[`Trip`](-trip/index.md)s comprises of a display trip (aka representative trip) and alternative trips. A display trip can be accessed via ``[`#getDisplayTrip()`](-trip-group/get-display-trip.md) while alternative trips can be retrieved via ``[`#getTrips()`](-trip-group/get-trips.md) minus ``[`#getDisplayTrip()`](-trip-group/get-display-trip.md). That's because ``[`#getTrips()`](-trip-group/get-trips.md) returns a list of ``[`Trip`](-trip/index.md)s including alternative trips and display trip. `open class TripGroup` |
| [TripGroupComparators](-trip-group-comparators/index.md) | `class TripGroupComparators` |
| [TripSegment](-trip-segment/index.md) | To go from A to B, sometimes we have to travel X, Y, Z locations between A and B. That means, we travel A to X, then X to Y, then Y to Z, then Z to B which is the destination. To show how to travel from A to X, we use ``[`TripSegment`](-trip-segment/index.md). So, in this case, a trip from A to B comprises 6 segments: - A segment whose type is ``[`SegmentType#DEPARTURE`](-segment-type/-d-e-p-a-r-t-u-r-e.md). - A segment from A to X. - A segment from X to Y. - A segment from Y to Z. - A segment from Z to B. - A segment whose type is ``[`SegmentType#ARRIVAL`](-segment-type/-a-r-r-i-v-a-l.md). `open class TripSegment : `[`IRealTimeElement`](../com.skedgo.tripkit.common.agenda/-i-real-time-element/index.md)`, `[`ITimeRange`](../com.skedgo.tripkit.common.model/-i-time-range/index.md) |
| [TripSegments](-trip-segments/index.md) | `class TripSegments` |
| [TurnByTurn](-turn-by-turn/index.md) | `enum class TurnByTurn` |
| [VehicleComponent](-vehicle-component/index.md) | `abstract class VehicleComponent` |
| [VehicleDrawables](-vehicle-drawables/index.md) | `class VehicleDrawables` |
| [VehicleMode](-vehicle-mode/index.md) | As of v11, this denotes local transport icons.`class VehicleMode` |
| [Visibilities](-visibilities/index.md) | `class Visibilities` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.String](kotlin.-string/index.md) |  |
| [org.joda.time.DateTime](org.joda.time.-date-time/index.md) |  |

### Properties

| Name | Summary |
|---|---|
| [actionAlert](action-alert.md) | `val `[`TripSegment`](-trip-segment/index.md)`.actionAlert: `[`RealtimeAlert`](../com.skedgo.tripkit.common.model/-realtime-alert/index.md)`?` |
| [dateTimeZone](date-time-zone.md) | `val `[`Location`](../com.skedgo.tripkit.common.model/-location/index.md)`.dateTimeZone: DateTimeZone` |
| [endDateTime](end-date-time.md) | Get an end date-time with time-zone.`val `[`Trip`](-trip/index.md)`.endDateTime: DateTime`<br>`val `[`TripSegment`](-trip-segment/index.md)`.endDateTime: DateTime` |
| [noActionAlerts](no-action-alerts.md) | `val `[`TripSegment`](-trip-segment/index.md)`.noActionAlerts: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RealtimeAlert`](../com.skedgo.tripkit.common.model/-realtime-alert/index.md)`!>?` |
| [SimilarLocationDegreeDifference](-similar-location-degree-difference.md) | `const val SimilarLocationDegreeDifference: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [startDateTime](start-date-time.md) | Gets a start date-time with time-zone.`val `[`Trip`](-trip/index.md)`.startDateTime: DateTime`<br>`val `[`TripSegment`](-trip-segment/index.md)`.startDateTime: DateTime` |

### Functions

| Name | Summary |
|---|---|
| [constructPlainText](construct-plain-text.md) | `fun `[`Trip`](-trip/index.md)`.constructPlainText(context: Context): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [containsAnyMode](contains-any-mode.md) | `fun `[`TripGroup`](-trip-group/index.md)`.containsAnyMode(modeIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsMode](contains-mode.md) | `fun `[`TripGroup`](-trip-group/index.md)`.containsMode(modeId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getModeIds](get-mode-ids.md) | `fun `[`Trip`](-trip/index.md)`.getModeIds(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [getSummarySegments](get-summary-segments.md) | Gets a list of [TripSegment](-trip-segment/index.md)s visible on the summary area of a [Trip](-trip/index.md).`fun `[`Trip`](-trip/index.md)`.getSummarySegments(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TripSegment`](-trip-segment/index.md)`>` |
| [getTrip](get-trip.md) | `fun `[`TripGroup`](-trip-group/index.md)`.getTrip(tripId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Trip`](-trip/index.md)`?` |
| [getTripSegment](get-trip-segment.md) | `fun `[`Trip`](-trip/index.md)`.getTripSegment(segmentId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`TripSegment`](-trip-segment/index.md)`?` |
| [hasWalkOnly](has-walk-only.md) | `fun `[`Trip`](-trip/index.md)`.hasWalkOnly(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isNear](is-near.md) | `fun `[`Location`](../com.skedgo.tripkit.common.model/-location/index.md)`.isNear(location: `[`Location`](../com.skedgo.tripkit.common.model/-location/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toInt](to-int.md) | `fun `[`ServiceColor`](-service-color/index.md)`.toInt(alpha: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
