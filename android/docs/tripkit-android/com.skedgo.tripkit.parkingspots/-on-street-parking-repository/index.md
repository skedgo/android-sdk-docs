[tripkit-android](../../index.md) / [com.skedgo.tripkit.parkingspots](../index.md) / [OnStreetParkingRepository](./index.md)

# OnStreetParkingRepository

`interface OnStreetParkingRepository`

### Functions

| Name | Summary |
|---|---|
| [getByCellIds](get-by-cell-ids.md) | `abstract fun getByCellIds(ids: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, southWest: `[`GeoPoint`](../../com.skedgo.tripkit.location/-geo-point/index.md)`, northEast: `[`GeoPoint`](../../com.skedgo.tripkit.location/-geo-point/index.md)`): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OnStreetParking`](../../com.skedgo.tripkit.parkingspots.models/-on-street-parking/index.md)`>>` |
| [getParkingDetails](get-parking-details.md) | `abstract fun getParkingDetails(onStreetParking: `[`OnStreetParking`](../../com.skedgo.tripkit.parkingspots.models/-on-street-parking/index.md)`): Single<`[`OnStreetParkingDetails`](../../skedgo.tripgo.parkingspots.models/-on-street-parking-details/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [OnStreetParkingRepositoryImpl](../../com.skedgo.tripkit.data.database.locations.onstreetparking/-on-street-parking-repository-impl/index.md) | `class OnStreetParkingRepositoryImpl : `[`OnStreetParkingRepository`](./index.md) |
