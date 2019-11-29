[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.dialog](../index.md) / [TripKitDateTimePickerDialogFragment](./index.md)

# TripKitDateTimePickerDialogFragment

`open class TripKitDateTimePickerDialogFragment : DialogFragment, OnTimeChangedListener`

A DialogFragment which allows a user to set a time and choose whether it is a departure time or an arrival time.

```
DialogFragment fragment = TripKitDateTimePickerDialogFragment.Builder()
          .withLocations(toLocation, fromLocation)
          .withTimeTag(timeTagForQuery)
          .build();
 
  fragment.show(supportFragmentManager, "timePicker")
```

### Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | Used to create a new instance of the fragment.`class Builder` |
| [OnTimeSelectedListener](-on-time-selected-listener/index.md) | Interface definition for a callback to be invoked when a time is selected.`interface OnTimeSelectedListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A DialogFragment which allows a user to set a time and choose whether it is a departure time or an arrival time.

```
DialogFragment fragment = TripKitDateTimePickerDialogFragment.Builder()
          .withLocations(toLocation, fromLocation)
          .withTimeTag(timeTagForQuery)
          .build();
 
  fragment.show(supportFragmentManager, "timePicker")  <br>```
<br>`TripKitDateTimePickerDialogFragment()` |

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
