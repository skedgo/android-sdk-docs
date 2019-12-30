[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database.locations.onstreetparking](../index.md) / [OnStreetParkingRepositoryImpl](./index.md)

# OnStreetParkingRepositoryImpl

`class OnStreetParkingRepositoryImpl : `[`OnStreetParkingRepository`](../../com.skedgo.tripkit.parkingspots/-on-street-parking-repository/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OnStreetParkingRepositoryImpl(onStreetParkingApi: `[`OnStreetParkingApi`](../-on-street-parking-api/index.md)`, tripKitDatabase: `[`TripKitDatabase`](../../com.skedgo.tripkit.data.database/-trip-kit-database/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [onStreetParkingApi](on-street-parking-api.md) | `val onStreetParkingApi: `[`OnStreetParkingApi`](../-on-street-parking-api/index.md) |
| [tripKitDatabase](trip-kit-database.md) | `val tripKitDatabase: `[`TripKitDatabase`](../../com.skedgo.tripkit.data.database/-trip-kit-database/index.md) |

### Functions

| Name | Summary |
|---|---|
| [getByCellIds](get-by-cell-ids.md) | `fun getByCellIds(ids: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, southWest: `[`GeoPoint`](../../com.skedgo.tripkit.location/-geo-point/index.md)`, northEast: `[`GeoPoint`](../../com.skedgo.tripkit.location/-geo-point/index.md)`): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OnStreetParking`](../../com.skedgo.tripkit.parkingspots.models/-on-street-parking/index.md)`>>` |
| [getParkingDetails](get-parking-details.md) | `fun getParkingDetails(onStreetParking: `[`OnStreetParking`](../../com.skedgo.tripkit.parkingspots.models/-on-street-parking/index.md)`): Single<`[`OnStreetParkingDetails`](../../skedgo.tripgo.parkingspots.models/-on-street-parking-details/index.md)`>` |
