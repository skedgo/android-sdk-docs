[tripkit-android](../../index.md) / [com.skedgo.android.common.model](../index.md) / [ServiceStop](./index.md)

# ServiceStop

`open class ServiceStop : `[`Location`](../-location/index.md)`, `[`WheelchairAccessible`](../-wheelchair-accessible/index.md)

Represents a future stop of a service in a trip.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServiceStop()`<br>`ServiceStop(location: `[`Location`](../-location/index.md)`!)` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`ServiceStop`](./index.md)`!>!` |
| [wheelchairAccessible](wheelchair-accessible.md) | `open val wheelchairAccessible: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |

### Functions

| Name | Summary |
|---|---|
| [departureSecs](departure-secs.md) | `open fun departureSecs(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [fillFrom](fill-from.md) | `open fun fillFrom(other: `[`Location`](../-location/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getArrivalTime](get-arrival-time.md) | `open fun getArrivalTime(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getCode](get-code.md) | `open fun getCode(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getDisplayTime](get-display-time.md) | `open fun getDisplayTime(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`!` |
| [getRelativeArrival](get-relative-arrival.md) | `open fun getRelativeArrival(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [getRelativeDeparture](get-relative-departure.md) | `open fun getRelativeDeparture(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [getShortName](get-short-name.md) | `open fun getShortName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getType](get-type.md) | `open fun getType(): `[`StopType`](../-stop-type/index.md)`!` |
| [setArrivalTime](set-arrival-time.md) | `open fun setArrivalTime(arrivalTime: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setCode](set-code.md) | `open fun setCode(code: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setDepartureSecs](set-departure-secs.md) | `open fun setDepartureSecs(secs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRelativeArrival](set-relative-arrival.md) | `open fun setRelativeArrival(relativeArrival: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRelativeDeparture](set-relative-departure.md) | `open fun setRelativeDeparture(relativeDeparture: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setShortName](set-short-name.md) | `open fun setShortName(shortName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setType](set-type.md) | `open fun setType(type: `[`StopType`](../-stop-type/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setWheelchairAccessible](set-wheelchair-accessible.md) | `open fun setWheelchairAccessible(wheelchairAccessible: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(out: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
