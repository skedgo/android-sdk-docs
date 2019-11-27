[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database.locations.bikepods](../index.md) / [BikePodRepositoryImpl](./index.md)

# BikePodRepositoryImpl

`class BikePodRepositoryImpl : `[`BikePodRepository`](../-bike-pod-repository/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BikePodRepositoryImpl(tripGoDatabase2: `[`TripKitDatabase`](../../com.skedgo.tripkit.data.database/-trip-kit-database/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [tripGoDatabase2](trip-go-database2.md) | `val tripGoDatabase2: `[`TripKitDatabase`](../../com.skedgo.tripkit.data.database/-trip-kit-database/index.md) |

### Functions

| Name | Summary |
|---|---|
| [getBikePod](get-bike-pod.md) | `fun getBikePod(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Single<`[`BikePodLocationEntity`](../-bike-pod-location-entity/index.md)`>` |
| [getBikePods](get-bike-pods.md) | `fun getBikePods(cellIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`BikePodLocationEntity`](../-bike-pod-location-entity/index.md)`>>` |
| [getBikePodsWithinBounds](get-bike-pods-within-bounds.md) | `fun getBikePodsWithinBounds(cellIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, southwest: `[`GeoPoint`](../../skedgo.tripkit.location/-geo-point/index.md)`, northEast: `[`GeoPoint`](../../skedgo.tripkit.location/-geo-point/index.md)`): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`BikePodLocationEntity`](../-bike-pod-location-entity/index.md)`>>` |
| [saveBikePods](save-bike-pods.md) | `fun saveBikePods(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, bikePods: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`BikePodLocationEntity`](../-bike-pod-location-entity/index.md)`>): Completable` |
