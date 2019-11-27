[tripkit-android](../../index.md) / [com.skedgo.android.common.model](../index.md) / [Query](./index.md)

# Query

`open class Query : Parcelable`

Represents a query to find routes from A to B.

 Note that, to avoid ``[`TransactionTooLargeException`](#), it's discouraged to pass any instance of ``[`Query`](./index.md) to ``[`Intent`](#) or ``[`Bundle`](#). The ``[`Parcelable`](#) is subject to deletion at anytime.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Query()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`Query`](./index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [clone](clone.md) | `open fun clone(): `[`Query`](./index.md)`!`<br>`open fun clone(cloneTransportMode: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Query`](./index.md)`!` |
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [destinationIsCurrentLocation](destination-is-current-location.md) | `open fun destinationIsCurrentLocation(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](equals.md) | `open fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getArriveBy](get-arrive-by.md) | `open fun getArriveBy(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getBudgetWeight](get-budget-weight.md) | `open fun getBudgetWeight(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getCyclingSpeed](get-cycling-speed.md) | `open fun getCyclingSpeed(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDepartAfter](get-depart-after.md) | `open fun getDepartAfter(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getEnvironmentWeight](get-environment-weight.md) | `open fun getEnvironmentWeight(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getExcludedStopCodes](get-excluded-stop-codes.md) | `open fun getExcludedStopCodes(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!` |
| [getFromLocation](get-from-location.md) | `open fun getFromLocation(): `[`Location`](../-location/index.md)`?` |
| [getHassleWeight](get-hassle-weight.md) | `open fun getHassleWeight(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMaxWalkingTime](get-max-walking-time.md) | In minutes. Note that this is only used for XUM project.`open fun getMaxWalkingTime(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getTimeTag](get-time-tag.md) | `open fun getTimeTag(): `[`TimeTag`](../-time-tag/index.md)`?` |
| [getTimeWeight](get-time-weight.md) | `open fun getTimeWeight(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getToLocation](get-to-location.md) | `open fun getToLocation(): `[`Location`](../-location/index.md)`?` |
| [getTransferTime](get-transfer-time.md) | `open fun getTransferTime(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getUnit](get-unit.md) | `open fun getUnit(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getWalkingSpeed](get-walking-speed.md) | `open fun getWalkingSpeed(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [hashCode](hash-code.md) | `open fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [originIsCurrentLocation](origin-is-current-location.md) | `open fun originIsCurrentLocation(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setBudgetWeight](set-budget-weight.md) | `open fun setBudgetWeight(weight: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setCyclingSpeed](set-cycling-speed.md) | `open fun setCyclingSpeed(cyclingSpeed: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setEnvironmentWeight](set-environment-weight.md) | `open fun setEnvironmentWeight(weight: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setExcludedStopCodes](set-excluded-stop-codes.md) | `open fun setExcludedStopCodes(excludedStopCodes: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setFromLocation](set-from-location.md) | `open fun setFromLocation(location: `[`Location`](../-location/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setHassleWeight](set-hassle-weight.md) | `open fun setHassleWeight(weight: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setMaxWalkingTime](set-max-walking-time.md) | In minutes. Note that this is only used for XUM project.`open fun setMaxWalkingTime(minutes: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTimeTag](set-time-tag.md) | `open fun setTimeTag(timeTag: `[`TimeTag`](../-time-tag/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTimeWeight](set-time-weight.md) | `open fun setTimeWeight(weight: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setToLocation](set-to-location.md) | `open fun setToLocation(location: `[`Location`](../-location/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTransferTime](set-transfer-time.md) | `open fun setTransferTime(transferTime: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setUnit](set-unit.md) | `open fun setUnit(unit: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setWalkingSpeed](set-walking-speed.md) | `open fun setWalkingSpeed(walkingSpeed: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [uuid](uuid.md) | `open fun uuid(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(dest: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
