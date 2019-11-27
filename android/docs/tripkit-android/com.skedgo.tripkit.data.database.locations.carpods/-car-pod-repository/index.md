[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database.locations.carpods](../index.md) / [CarPodRepository](./index.md)

# CarPodRepository

`open class CarPodRepository`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `CarPodRepository(database: `[`TripKitDatabase`](../../com.skedgo.tripkit.data.database/-trip-kit-database/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [getCarPod](get-car-pod.md) | `fun getCarPod(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Single<`[`CarPod`](../../skedgo.tripkit.locations/-car-pod/index.md)`>` |
| [getCarPodsByCellIds](get-car-pods-by-cell-ids.md) | `fun getCarPodsByCellIds(cellIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CarPod`](../../skedgo.tripkit.locations/-car-pod/index.md)`>>` |
| [getCarPodsByCellIdsWithinBounds](get-car-pods-by-cell-ids-within-bounds.md) | `fun getCarPodsByCellIdsWithinBounds(cellIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, southwest: `[`GeoPoint`](../../skedgo.tripkit.location/-geo-point/index.md)`, northEast: `[`GeoPoint`](../../skedgo.tripkit.location/-geo-point/index.md)`): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CarPod`](../../skedgo.tripkit.locations/-car-pod/index.md)`>>` |
| [saveCarPods](save-car-pods.md) | `fun saveCarPods(carPodEntities: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`CarPodEntity`](../-car-pod-entity/index.md)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CarPodVehicle`](../-car-pod-vehicle/index.md)`>?>>): Completable` |
