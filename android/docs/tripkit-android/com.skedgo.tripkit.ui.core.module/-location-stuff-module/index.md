[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.core.module](../index.md) / [LocationStuffModule](./index.md)

# LocationStuffModule

`@Module class LocationStuffModule`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LocationStuffModule()` |

### Functions

| Name | Summary |
|---|---|
| [locationStream](location-stream.md) | `fun locationStream(client: RxFusedLocationProviderClient): Observable<Location>` |
| [rxFusedLocationProviderClient](rx-fused-location-provider-client.md) | `fun rxFusedLocationProviderClient(context: Context): RxFusedLocationProviderClient` |
| [userGeoPointRepository](user-geo-point-repository.md) | `fun userGeoPointRepository(getLocationUpdates: Provider<Observable<Location>>, getNow: `[`GetNow`](../../com.skedgo.tripkit.time/-get-now/index.md)`): UserGeoPointRepository` |
