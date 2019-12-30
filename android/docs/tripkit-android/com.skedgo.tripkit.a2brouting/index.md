[tripkit-android](../index.md) / [com.skedgo.tripkit.a2brouting](./index.md)

## Package com.skedgo.tripkit.a2brouting

### Types

| Name | Summary |
|---|---|
| [A2bRoutingApi](-a2b-routing-api/index.md) | Calculates door-to-door trips for the specified mode(s). See more at https://skedgo.github.io/tripgo-api/#tag/Routing%2Fpaths%2F~1routing.json%2Fget.`interface A2bRoutingApi` |
| [A2bRoutingDataModule](-a2b-routing-data-module/index.md) | `class A2bRoutingDataModule` |
| [A2bRoutingRequest](-a2b-routing-request/index.md) | `abstract class A2bRoutingRequest` |
| [FailoverA2bRoutingApi](-failover-a2b-routing-api/index.md) | A wrapper of ``[`A2bRoutingApi`](-a2b-routing-api/index.md) that requests `routing.json` on multiple servers w/ failover.`open class FailoverA2bRoutingApi` |
| [FillIdentifiers](-fill-identifiers/index.md) | Fills id for ``[`Trip`](../com.skedgo.tripkit.routing/-trip/index.md).`class FillIdentifiers : Function<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripGroup`](../com.skedgo.tripkit.routing/-trip-group/index.md)`!>!, `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripGroup`](../com.skedgo.tripkit.routing/-trip-group/index.md)`!>!>` |
| [GetNonTravelledLineForTrip](-get-non-travelled-line-for-trip/index.md) | `class GetNonTravelledLineForTrip` |
| [GetTravelledLineForTrip](-get-travelled-line-for-trip/index.md) | `class GetTravelledLineForTrip` |
| [RequestTime](-request-time/index.md) | `sealed class RequestTime` |
| [RouteService](-route-service/index.md) | `interface RouteService` |
| [SelectBestDisplayTrip](-select-best-display-trip/index.md) | Selects display trip which has lowest weighted score. `class SelectBestDisplayTrip : Function<`[`TripGroup`](../com.skedgo.tripkit.routing/-trip-group/index.md)`!, `[`TripGroup`](../com.skedgo.tripkit.routing/-trip-group/index.md)`!>` |
| [SingleRouteService](-single-route-service/index.md) | A decorator of [RouteService](-route-service/index.md) that performs only one routing request. For example, if we ask it to route from A to B, and while that request is still progress and later we ask it to route from C to B, then the request A-to-B will be cancelled. Cancellation is invoked asynchronously. That means the execution of the request C-to-D doesn't have to wait for the cancellation of the request A-to-B to be done to get started.`class SingleRouteService : `[`RouteService`](-route-service/index.md) |
| [ToWeightingProfileString](-to-weighting-profile-string/index.md) | `object ToWeightingProfileString` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Int](kotlin.-int/index.md) |  |
