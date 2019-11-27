[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database.locations.bikepods](../index.md) / [BikePodDao](./index.md)

# BikePodDao

`abstract class BikePodDao`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BikePodDao()` |

### Functions

| Name | Summary |
|---|---|
| [getAllByCellsAndLatLngBounds](get-all-by-cells-and-lat-lng-bounds.md) | `abstract fun getAllByCellsAndLatLngBounds(cellIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, southWestLat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, southWestLng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, northEastLat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, northEastLng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): Flowable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`BikePodLocationEntity`](../-bike-pod-location-entity/index.md)`>>` |
| [getAllInCells](get-all-in-cells.md) | `abstract fun getAllInCells(cellIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): Flowable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`BikePodLocationEntity`](../-bike-pod-location-entity/index.md)`>>` |
| [getById](get-by-id.md) | `abstract fun getById(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`BikePodLocationEntity`](../-bike-pod-location-entity/index.md) |
| [saveAll](save-all.md) | `abstract fun saveAll(bikePods: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`BikePodLocationEntity`](../-bike-pod-location-entity/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
