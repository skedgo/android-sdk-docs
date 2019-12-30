[tripkit-android](../../index.md) / [com.skedgo.tripkit.a2brouting](../index.md) / [SingleRouteService](./index.md)

# SingleRouteService

`class SingleRouteService : `[`RouteService`](../-route-service/index.md)

A decorator of [RouteService](../-route-service/index.md) that performs only one routing request.
For example, if we ask it to route from A to B, and while that request
is still progress and later we ask it to route from C to B,
then the request A-to-B will be cancelled.
Cancellation is invoked asynchronously. That means the execution
of the request C-to-D doesn't have to wait for
the cancellation of the request A-to-B to be done to get started.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A decorator of [RouteService](../-route-service/index.md) that performs only one routing request. For example, if we ask it to route from A to B, and while that request is still progress and later we ask it to route from C to B, then the request A-to-B will be cancelled. Cancellation is invoked asynchronously. That means the execution of the request C-to-D doesn't have to wait for the cancellation of the request A-to-B to be done to get started.`SingleRouteService(routeService: `[`RouteService`](../-route-service/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [routeAsync](route-async.md) | To find routes from A to B asynchronously.`fun routeAsync(query: `[`Query`](../../com.skedgo.tripkit.common.model/-query/index.md)`, transportModeFilter: `[`TransportModeFilter`](../../com.skedgo.tripkit/-transport-mode-filter/index.md)`, transitModeFilter: `[`TransitModeFilter`](../../com.skedgo.tripkit/-transit-mode-filter/index.md)`): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TripGroup`](../../com.skedgo.tripkit.routing/-trip-group/index.md)`>>` |
