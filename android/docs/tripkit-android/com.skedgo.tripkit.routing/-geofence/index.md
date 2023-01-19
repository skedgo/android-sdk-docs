[tripkit-android](../../index.md) / [com.skedgo.tripkit.routing](../index.md) / [Geofence](./index.md)

# Geofence

`data class Geofence`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;]| `Geofence(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, trigger: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, center: `[`Coordinate`](coordinate.md)`, radius: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/)`, messageType: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, messageTitle: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, messageBody: `[`String`](https://android.developer.tripgo.com/tripkit-android/com.skedgo.tripkit.routing/-mode-info/)`)` |
 
### Properties

| Name | Summary |
|---|---|
| id | `val id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| type | `val type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| trigger | `val trigger: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| center | `val center: `[`Coordinate`](coordinate.md) |
| radius | `val center: `[`Doublle`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/) |
| messageType | `val messageType: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| messageTitle | `val messageTitle: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| messageBody | `val messageBody: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Functions

| Name | Summary |
|---|---|
| computeAndSetTimeline | `fun computeAndSetTimeline(tripEndDateTimeInMillis:`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/)`):`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/) |