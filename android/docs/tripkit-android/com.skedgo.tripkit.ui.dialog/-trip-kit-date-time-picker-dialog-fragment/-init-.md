[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.dialog](../index.md) / [TripKitDateTimePickerDialogFragment](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`TripKitDateTimePickerDialogFragment()`

A DialogFragment which allows a user to set a time and choose whether it is a departure time or an arrival time.

```
    DialogFragment fragment = TripKitDateTimePickerDialogFragment.Builder()
                                .withLocations(toLocation, fromLocation)
                                .withTimeTag(timeTagForQuery)
                                .build();

    fragment.show(supportFragmentManager, "timePicker")
```

