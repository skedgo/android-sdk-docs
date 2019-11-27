[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.trip.options](../index.md) / [InterCityTimePickerViewModel](./index.md)

# InterCityTimePickerViewModel

`open class InterCityTimePickerViewModel : `[`ITimePickerViewModel`](../../com.skedgo.tripkit.ui.trip.details.viewmodel/-i-time-picker-view-model/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `InterCityTimePickerViewModel(context: Context, bus: Bus, getNow: `[`GetNow`](../../com.skedgo.tripkit.time/-get-now/index.md)`, defaultTimezone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!)` |

### Properties

| Name | Summary |
|---|---|
| [ARG_ARRIVAL_TIMEZONE](-a-r-g_-a-r-r-i-v-a-l_-t-i-m-e-z-o-n-e.md) | `static val ARG_ARRIVAL_TIMEZONE: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_DEPARTURE_TIMEZONE](-a-r-g_-d-e-p-a-r-t-u-r-e_-t-i-m-e-z-o-n-e.md) | `static val ARG_DEPARTURE_TIMEZONE: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_TIME_IN_MILLIS](-a-r-g_-t-i-m-e_-i-n_-m-i-l-l-i-s.md) | `static val ARG_TIME_IN_MILLIS: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_TIME_TYPE](-a-r-g_-t-i-m-e_-t-y-p-e.md) | `static val ARG_TIME_TYPE: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [dates](dates.md) | `open fun dates(): ObservableField<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!>!` |
| [done](done.md) | `open fun done(): `[`TimeTag`](../../com.skedgo.android.common.model/-time-tag/index.md)`!` |
| [getHour](get-hour.md) | `open fun getHour(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMinute](get-minute.md) | `open fun getMinute(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [handleArguments](handle-arguments.md) | `open fun handleArguments(args: Bundle!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [isLeaveAfter](is-leave-after.md) | `open fun isLeaveAfter(): ObservableBoolean!` |
| [leaveNow](leave-now.md) | `open fun leaveNow(): `[`TimeTag`](../../com.skedgo.android.common.model/-time-tag/index.md)`!` |
| [selectedPosition](selected-position.md) | `open fun selectedPosition(): ObservableInt!` |
| [updateTime](update-time.md) | `open fun updateTime(hour: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, minute: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
