[tripkit-android](../../index.md) / [com.skedgo.tripkit.routing](../index.md) / [Shape](./index.md)

# Shape

`open class Shape : Parcelable`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Shape()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`Shape`](./index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getEncodedWaypoints](get-encoded-waypoints.md) | `open fun getEncodedWaypoints(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getId](get-id.md) | `open fun getId(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getServiceColor](get-service-color.md) | `open fun getServiceColor(): `[`ServiceColor`](../-service-color/index.md)`!` |
| [getStops](get-stops.md) | `open fun getStops(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`ServiceStop`](../../com.skedgo.tripkit.common.model/-service-stop/index.md)`!>?` |
| [isTravelled](is-travelled.md) | `open fun isTravelled(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>`open fun isTravelled(isTravelled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setEncodedWaypoints](set-encoded-waypoints.md) | `open fun setEncodedWaypoints(encodedWaypoints: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setId](set-id.md) | `open fun setId(id: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceColor](set-service-color.md) | `open fun setServiceColor(serviceColor: `[`ServiceColor`](../-service-color/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStops](set-stops.md) | `open fun setStops(stops: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`ServiceStop`](../../com.skedgo.tripkit.common.model/-service-stop/index.md)`!>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(out: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
