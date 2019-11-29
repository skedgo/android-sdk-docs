[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.locationhelper](../index.md) / [LocationHelper](./index.md)

# LocationHelper

`class LocationHelper`

A simple wrapper around [FusedLocationProviderClient](https://developers.google.com/android/reference/com/google/android/gms/location/FusedLocationProviderClient).

It is your responsibility to make sure that your app has requested the correct permissions to get location.

### Types

| Name | Summary |
|---|---|
| [OnLocationFoundListener](-on-location-found-listener/index.md) | Interface definition for a callback that will be called when a location is either found, or an error occurs.`interface OnLocationFoundListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A simple wrapper around [FusedLocationProviderClient](https://developers.google.com/android/reference/com/google/android/gms/location/FusedLocationProviderClient).`LocationHelper(context: Context)` |

### Functions

| Name | Summary |
|---|---|
| [getCurrentLocation](get-current-location.md) | Retrieves the current location.`fun getCurrentLocation(listener: OnLocationFoundListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun getCurrentLocation(listener: (`[`Location`](../../com.skedgo.android.common.model/-location/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
