[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.routingstatus](../index.md) / [RoutingStatusRepositoryImpl](./index.md)

# RoutingStatusRepositoryImpl

`@Singleton class RoutingStatusRepositoryImpl : `[`RoutingStatusRepository`](../../skedgo.tripkit.routingstatus/-routing-status-repository/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoutingStatusRepositoryImpl(routingStatusStore: RoutingStatusStore)` |

### Functions

| Name | Summary |
|---|---|
| [getRoutingStatus](get-routing-status.md) | `fun getRoutingStatus(requestId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`RoutingStatus`](../../skedgo.tripkit.routingstatus/-routing-status/index.md)`>` |
| [putRoutingStatus](put-routing-status.md) | `fun putRoutingStatus(routingStatus: `[`RoutingStatus`](../../skedgo.tripkit.routingstatus/-routing-status/index.md)`): Completable` |
