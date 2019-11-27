[tripkit-android](../../index.md) / [com.skedgo.android.common.util](../index.md) / [SphericalUtil](index.md) / [computeOffset](./compute-offset.md)

# computeOffset

`open static fun computeOffset(from: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, distance: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, heading: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!`

Returns the TripKitLatLng resulting from moving a distance from an origin in the specified heading (expressed in degrees clockwise from north).

### Parameters

`from` - [TripKitLatLng](../-trip-kit-lat-lng/index.md)!: The TripKitLatLng from which to start.

`distance` - [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html): The distance to travel.

`heading` - [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html): The heading in degrees clockwise from north.