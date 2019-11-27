[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database.locations.carpods](../index.md) / [CarPodDao](./index.md)

# CarPodDao

`interface CarPodDao`

### Functions

| Name | Summary |
|---|---|
| [getCarPodById](get-car-pod-by-id.md) | `abstract fun getCarPodById(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`CarPodEntity`](../-car-pod-entity/index.md) |
| [getCarPodsByCellIds](get-car-pods-by-cell-ids.md) | `abstract fun getCarPodsByCellIds(cellIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): Flowable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CarPodEntity`](../-car-pod-entity/index.md)`>>` |
| [getCarPodsByCellIdsWithinBounds](get-car-pods-by-cell-ids-within-bounds.md) | `abstract fun getCarPodsByCellIdsWithinBounds(cellIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, southWestLat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, southWestLng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, northEastLat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, northEastLng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): Flowable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CarPodEntity`](../-car-pod-entity/index.md)`>>` |
| [getVehiclesByCarPodId](get-vehicles-by-car-pod-id.md) | `abstract fun getVehiclesByCarPodId(carPodId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CarPodVehicle`](../-car-pod-vehicle/index.md)`>?` |
| [saveAll](save-all.md) | `abstract fun saveAll(entities: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CarPodEntity`](../-car-pod-entity/index.md)`>, vehicles: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CarPodVehicle`](../-car-pod-vehicle/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
