[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.locationhelper](../index.md) / [LocationHelper](index.md) / [getCurrentLocation](./get-current-location.md)

# getCurrentLocation

`fun getCurrentLocation(listener: OnLocationFoundListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Retrieves the current location.

### Parameters

`listener` - The callback to be called when a location is found.`fun getCurrentLocation(listener: (`[`Location`](../../com.skedgo.tripkit.common.model/-location/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Retrieves the current location.

### Parameters

`listener` - A function to be called when a location is found.

`error` - A function to be called when an error occurred.