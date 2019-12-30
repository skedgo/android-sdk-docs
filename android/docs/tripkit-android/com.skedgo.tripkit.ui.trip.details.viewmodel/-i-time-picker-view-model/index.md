[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.trip.details.viewmodel](../index.md) / [ITimePickerViewModel](./index.md)

# ITimePickerViewModel

`interface ITimePickerViewModel`

### Functions

| Name | Summary |
|---|---|
| [dates](dates.md) | `abstract fun dates(): ObservableField<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!>!` |
| [done](done.md) | `abstract fun done(): `[`TimeTag`](../../com.skedgo.tripkit.common.model/-time-tag/index.md)`!` |
| [getHour](get-hour.md) | `abstract fun getHour(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMinute](get-minute.md) | `abstract fun getMinute(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [handleArguments](handle-arguments.md) | `abstract fun handleArguments(args: Bundle!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [isLeaveAfter](is-leave-after.md) | `abstract fun isLeaveAfter(): ObservableBoolean!` |
| [leaveNow](leave-now.md) | `abstract fun leaveNow(): `[`TimeTag`](../../com.skedgo.tripkit.common.model/-time-tag/index.md)`!` |
| [selectedPosition](selected-position.md) | `abstract fun selectedPosition(): ObservableInt!` |
| [updateTime](update-time.md) | `abstract fun updateTime(hour: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, minute: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [InterCityTimePickerViewModel](../../com.skedgo.tripkit.ui.trip.options/-inter-city-time-picker-view-model/index.md) | `open class InterCityTimePickerViewModel : `[`ITimePickerViewModel`](./index.md) |
