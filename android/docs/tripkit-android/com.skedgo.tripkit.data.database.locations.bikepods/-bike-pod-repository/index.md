[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database.locations.bikepods](../index.md) / [BikePodRepository](./index.md)

# BikePodRepository

`interface BikePodRepository`

### Functions

| Name | Summary |
|---|---|
| [getBikePod](get-bike-pod.md) | `abstract fun getBikePod(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Single<`[`BikePodLocationEntity`](../-bike-pod-location-entity/index.md)`>` |
| [getBikePods](get-bike-pods.md) | `abstract fun getBikePods(cellIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`BikePodLocationEntity`](../-bike-pod-location-entity/index.md)`>>` |
| [getBikePodsWithinBounds](get-bike-pods-within-bounds.md) | `abstract fun getBikePodsWithinBounds(cellIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, southwest: `[`GeoPoint`](../../skedgo.tripkit.location/-geo-point/index.md)`, northEast: `[`GeoPoint`](../../skedgo.tripkit.location/-geo-point/index.md)`): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`BikePodLocationEntity`](../-bike-pod-location-entity/index.md)`>>` |
| [saveBikePods](save-bike-pods.md) | `abstract fun saveBikePods(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, bikePods: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`BikePodLocationEntity`](../-bike-pod-location-entity/index.md)`>): Completable` |

### Inheritors

| Name | Summary |
|---|---|
| [BikePodRepositoryImpl](../-bike-pod-repository-impl/index.md) | `class BikePodRepositoryImpl : `[`BikePodRepository`](./index.md) |
