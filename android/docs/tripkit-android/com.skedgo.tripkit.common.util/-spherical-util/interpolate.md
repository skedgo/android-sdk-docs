[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.util](../index.md) / [SphericalUtil](index.md) / [interpolate](./interpolate.md)

# interpolate

`open static fun interpolate(from: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, to: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, fraction: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!`

Returns the TripKitLatLng which lies the given fraction of the way between the origin TripKitLatLng and the destination TripKitLatLng.

### Parameters

`from` - [TripKitLatLng](../-trip-kit-lat-lng/index.md)!: The TripKitLatLng from which to start.

`to` - [TripKitLatLng](../-trip-kit-lat-lng/index.md)!: The TripKitLatLng toward which to travel.

`fraction` - [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html): A fraction of the distance to travel.

**Return**
[TripKitLatLng](../-trip-kit-lat-lng/index.md)!: The interpolated TripKitLatLng.

