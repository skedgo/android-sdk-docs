[tripkit-android](../../index.md) / [com.skedgo.tripkit.routingstatus](../index.md) / [RoutingStatusRepository](./index.md)

# RoutingStatusRepository

`interface RoutingStatusRepository`

### Functions

| Name | Summary |
|---|---|
| [getRoutingStatus](get-routing-status.md) | `abstract fun getRoutingStatus(requestId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`RoutingStatus`](../-routing-status/index.md)`>` |
| [putRoutingStatus](put-routing-status.md) | `abstract fun putRoutingStatus(routingStatus: `[`RoutingStatus`](../-routing-status/index.md)`): Completable` |

### Inheritors

| Name | Summary |
|---|---|
| [RoutingStatusRepositoryImpl](../../com.skedgo.tripkit.data.routingstatus/-routing-status-repository-impl/index.md) | `class RoutingStatusRepositoryImpl : `[`RoutingStatusRepository`](./index.md) |
