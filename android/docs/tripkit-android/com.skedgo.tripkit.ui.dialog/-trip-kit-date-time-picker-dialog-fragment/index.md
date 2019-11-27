[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.dialog](../index.md) / [TripKitDateTimePickerDialogFragment](./index.md)

# TripKitDateTimePickerDialogFragment

`open class TripKitDateTimePickerDialogFragment : DialogFragment, OnTimeChangedListener`

### Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | `class Builder` |
| [OnTimeSelectedListener](-on-time-selected-listener/index.md) | `interface OnTimeSelectedListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TripKitDateTimePickerDialogFragment()` |

### Properties

| Name | Summary |
|---|---|
| [selectionChangedRelay](selection-changed-relay.md) | `var selectionChangedRelay: PublishRelay<`[`TimeTag`](../../com.skedgo.android.common.model/-time-tag/index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [onClickArriveBy](on-click-arrive-by.md) | `open fun onClickArriveBy(view: View!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onClickLeaveAfter](on-click-leave-after.md) | `open fun onClickLeaveAfter(view: View!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreate](on-create.md) | `open fun onCreate(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateDialog](on-create-dialog.md) | `open fun onCreateDialog(savedInstanceState: Bundle?): Dialog` |
| [onTimeChanged](on-time-changed.md) | `open fun onTimeChanged(timePicker: TimePicker!, hour: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, minute: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOnTimeSelectedListener](set-on-time-selected-listener.md) | `open fun setOnTimeSelectedListener(listener: OnTimeSelectedListener!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
