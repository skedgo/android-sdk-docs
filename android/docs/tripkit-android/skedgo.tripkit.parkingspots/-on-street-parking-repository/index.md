[tripkit-android](../../index.md) / [skedgo.tripkit.parkingspots](../index.md) / [OnStreetParkingRepository](./index.md)

# OnStreetParkingRepository

`interface OnStreetParkingRepository`

### Functions

| Name | Summary |
|---|---|
| [getByCellIds](get-by-cell-ids.md) | `abstract fun getByCellIds(ids: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, southWest: `[`GeoPoint`](../../skedgo.tripkit.location/-geo-point/index.md)`, northEast: `[`GeoPoint`](../../skedgo.tripkit.location/-geo-point/index.md)`): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OnStreetParking`](../../skedgo.tripkit.parkingspots.models/-on-street-parking/index.md)`>>` |
| [getParkingDetails](get-parking-details.md) | `abstract fun getParkingDetails(onStreetParking: `[`OnStreetParking`](../../skedgo.tripkit.parkingspots.models/-on-street-parking/index.md)`): Single<`[`OnStreetParkingDetails`](../../skedgo.tripgo.parkingspots.models/-on-street-parking-details/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [OnStreetParkingRepositoryImpl](../../com.skedgo.tripkit.data.database.locations.onstreetparking/-on-street-parking-repository-impl/index.md) | `class OnStreetParkingRepositoryImpl : `[`OnStreetParkingRepository`](./index.md) |
