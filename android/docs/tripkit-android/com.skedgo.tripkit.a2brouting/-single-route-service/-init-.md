[tripkit-android](../../index.md) / [com.skedgo.tripkit.a2brouting](../index.md) / [SingleRouteService](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`SingleRouteService(routeService: `[`RouteService`](../-route-service/index.md)`)`

A decorator of [RouteService](../-route-service/index.md) that performs only one routing request.
For example, if we ask it to route from A to B, and while that request
is still progress and later we ask it to route from C to B,
then the request A-to-B will be cancelled.
Cancellation is invoked asynchronously. That means the execution
of the request C-to-D doesn't have to wait for
the cancellation of the request A-to-B to be done to get started.

