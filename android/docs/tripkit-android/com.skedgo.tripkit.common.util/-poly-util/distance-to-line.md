[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.util](../index.md) / [PolyUtil](index.md) / [distanceToLine](./distance-to-line.md)

# distanceToLine

`open static fun distanceToLine(p: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, start: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, end: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)

Computes the distance on the sphere between the point p and the line segment start to end.

### Parameters

`p` - [TripKitLatLng](../-trip-kit-lat-lng/index.md)!: the point to be measured

`start` - [TripKitLatLng](../-trip-kit-lat-lng/index.md)!: the beginning of the line segment

`end` - [TripKitLatLng](../-trip-kit-lat-lng/index.md)!: the end of the line segment

**Return**
[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html): the distance in meters (assuming spherical earth)

