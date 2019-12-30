[tripkit-android](../../../index.md) / [com.skedgo.tripkit.ui.locationhelper](../../index.md) / [LocationHelper](../index.md) / [OnLocationFoundListener](./index.md)

# OnLocationFoundListener

`interface OnLocationFoundListener`

Interface definition for a callback that will be called when a location is either found, or an error occurs.

### Functions

| Name | Summary |
|---|---|
| [locationError](location-error.md) | Called when an error occurred.`abstract fun locationError(error: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [locationFound](location-found.md) | Called when a location is found.`abstract fun locationFound(location: `[`Location`](../../../com.skedgo.tripkit.common.model/-location/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
