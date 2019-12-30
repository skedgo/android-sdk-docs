[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.dialog](../index.md) / [TripKitDateTimePickerDialogFragment](./index.md)

# TripKitDateTimePickerDialogFragment

`class TripKitDateTimePickerDialogFragment : DialogFragment, OnTimeChangedListener`

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
| [&lt;init&gt;](-init-.md) | A DialogFragment which allows a user to set a time and choose whether it is a departure time or an arrival time.`TripKitDateTimePickerDialogFragment()` |

### Functions

| Name | Summary |
|---|---|
| [setOnTimeSelectedListener](set-on-time-selected-listener.md) | `fun setOnTimeSelectedListener(listener: OnTimeSelectedListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun setOnTimeSelectedListener(listener: (`[`TimeTag`](../../com.skedgo.tripkit.common.model/-time-tag/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
