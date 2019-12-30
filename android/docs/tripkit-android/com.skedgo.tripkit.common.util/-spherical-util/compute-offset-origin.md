[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.util](../index.md) / [SphericalUtil](index.md) / [computeOffsetOrigin](./compute-offset-origin.md)

# computeOffsetOrigin

`open static fun computeOffsetOrigin(to: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, distance: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, heading: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!`

Returns the location of origin when provided with a TripKitLatLng destination, meters travelled and original heading. Headings are expressed in degrees clockwise from North. This function returns null when no solution is available.

### Parameters

`to` - [TripKitLatLng](../-trip-kit-lat-lng/index.md)!: The destination TripKitLatLng.

`distance` - [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html): The distance travelled, in meters.

`heading` - [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html): The heading in degrees clockwise from north.