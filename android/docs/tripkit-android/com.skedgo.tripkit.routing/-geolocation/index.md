[tripkit-android](../../index.md) / [com.skedgo.tripkit.routing](../index.md) / [GeoLocation](./index.md)

# GeoLocation

`object GeoLocation`
 
### Functions

| Name | Summary |
|---|---|
| init | `fun init(context: `[`Context`](https://developer.android.com/reference/android/content/Context)`)` |
| createGeoFences | `fun createGeoFences(geofences: List<`[`Geofence`](../-geofence/index.md)`>)` |
| createGeoFencingRequest | `private fun createGeoFencingRequest(): `[`GeofencingRequest`](https://developers.google.com/android/reference/com/google/android/gms/location/GeofencingRequest)`?` |
| clearGeofences | `fun clearGeofences()` |
| removeGeoFences | `fun removeGeoFences(onRemoveCallback: (() -> Unit))` |