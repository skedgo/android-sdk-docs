[tripkit-android](../../index.md) / [com.skedgo.tripkit.parkingspots](../index.md) / [ParkingRepository](./index.md)

# ParkingRepository

`interface ParkingRepository`

### Functions

| Name | Summary |
|---|---|
| [fetchCarParks](fetch-car-parks.md) | `abstract fun fetchCarParks(center: `[`GeoPoint`](../../com.skedgo.tripkit.location/-geo-point/index.md)`, cellIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, zoomLevel: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OffStreetParking`](../../com.skedgo.tripkit.parkingspots.models/-off-street-parking/index.md)`>>` |
| [getByCellIds](get-by-cell-ids.md) | `abstract fun getByCellIds(ids: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OffStreetParking`](../../com.skedgo.tripkit.parkingspots.models/-off-street-parking/index.md)`>>` |
