[tripkit-android](../../index.md) / [com.skedgo.tripkit.a2brouting](../index.md) / [RouteService](index.md) / [routeAsync](./route-async.md)

# routeAsync

`abstract fun routeAsync(query: `[`Query`](../../com.skedgo.android.common.model/-query/index.md)`, transportModeFilter: `[`TransportModeFilter`](../../com.skedgo.tripkit/-transport-mode-filter/index.md)` = object : TransportModeFilter {}, transitModeFilter: `[`TransitModeFilter`](../../com.skedgo.tripkit/-transit-mode-filter/index.md)` = object : TransitModeFilter {}): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TripGroup`](../../skedgo.tripkit.routing/-trip-group/index.md)`>>`

To find routes from A to B asynchronously.

**Return**

An [Observable](#) which emits multiple of list of [TripGroup](../../skedgo.tripkit.routing/-trip-group/index.md)s,
and then completes. That means, when we subscribe it via [Observable.subscribe](#),
it will emit the first list of [TripGroup](../../skedgo.tripkit.routing/-trip-group/index.md)s. And then it will emit the second
list of [TripGroup](../../skedgo.tripkit.routing/-trip-group/index.md)s. There may be a certain delay between the emission
of the first [TripGroup](../../skedgo.tripkit.routing/-trip-group/index.md) list and the second [TripGroup](../../skedgo.tripkit.routing/-trip-group/index.md) list due to network latency.



By default, the returned [Observable](#) will operate on [rx.schedulers.Schedulers.io](#).
So be sure to [Observable.observeOn](#) with [rx.android.schedulers.AndroidSchedulers.mainThread](#)
to render [TripGroup](../../skedgo.tripkit.routing/-trip-group/index.md)s on the main thread.

