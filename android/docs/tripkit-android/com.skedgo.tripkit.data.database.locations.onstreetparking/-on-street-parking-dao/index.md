[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database.locations.onstreetparking](../index.md) / [OnStreetParkingDao](./index.md)

# OnStreetParkingDao

`interface OnStreetParkingDao`

### Functions

| Name | Summary |
|---|---|
| [getByCellIds](get-by-cell-ids.md) | `abstract fun getByCellIds(ids: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, southWestLat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, southWestLng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, northEastLat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, northEastLng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): Flowable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OnStreetParkingEntity`](../-on-street-parking-entity/index.md)`>>` |
| [saveAll](save-all.md) | `abstract fun saveAll(onStreetParkings: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OnStreetParkingEntity`](../-on-street-parking-entity/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
