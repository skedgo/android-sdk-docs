[tripkit-android](../../index.md) / [com.skedgo.android.common.model](../index.md) / [TimeTag](./index.md)

# TimeTag

`open class TimeTag : Parcelable`

### Annotations

| Name | Summary |
|---|---|
| [TimeType](-time-type/index.md) | See: http://tools.android.com/tech-docs/support-annotations.`class TimeType` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TimeTag(in: Parcel!)`<br>`TimeTag()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`TimeTag`](./index.md)`!>!` |
| [TIME_TYPE_ARRIVE_BY](-t-i-m-e_-t-y-p-e_-a-r-r-i-v-e_-b-y.md) | `static val TIME_TYPE_ARRIVE_BY: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [TIME_TYPE_LEAVE_AFTER](-t-i-m-e_-t-y-p-e_-l-e-a-v-e_-a-f-t-e-r.md) | `static val TIME_TYPE_LEAVE_AFTER: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Functions

| Name | Summary |
|---|---|
| [createForArriveBy](create-for-arrive-by.md) | `open static fun createForArriveBy(seconds: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`TimeTag`](./index.md)`!` |
| [createForLeaveAfter](create-for-leave-after.md) | `open static fun createForLeaveAfter(seconds: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`TimeTag`](./index.md)`!` |
| [createForLeaveNow](create-for-leave-now.md) | `open static fun createForLeaveNow(): `[`TimeTag`](./index.md)`!` |
| [createForTimeType](create-for-time-type.md) | `open static fun createForTimeType(timeType: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, seconds: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`TimeTag`](./index.md)`!` |
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getTimeInMillis](get-time-in-millis.md) | `open fun getTimeInMillis(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getTimeInSecs](get-time-in-secs.md) | `open fun getTimeInSecs(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getType](get-type.md) | `open fun getType(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isDynamic](is-dynamic.md) | `open fun isDynamic(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setIsDynamic](set-is-dynamic.md) | `open fun setIsDynamic(isDynamic: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTimeInSecs](set-time-in-secs.md) | `open fun setTimeInSecs(timeInSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setType](set-type.md) | `open fun setType(type: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(dest: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [formatString](../../com.skedgo.tripkit.ui.utils/format-string.md) | `fun `[`TimeTag`](./index.md)`.formatString(context: Context, timezone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [toRoutingTime](../../com.skedgo.tripkit.ui.trip/to-routing-time.md) | `fun `[`TimeTag`](./index.md)`.toRoutingTime(tz: DateTimeZone): `[`RoutingTime`](../../com.skedgo.tripkit.ui.trip/-routing-time.md) |
