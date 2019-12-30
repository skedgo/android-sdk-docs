[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.timetables](../index.md) / [TimetableFragment](./index.md)

# TimetableFragment

`class TimetableFragment : `[`AbstractTripKitFragment`](../../com.skedgo.tripkit.ui.core/-abstract-trip-kit-fragment/index.md)`, OnClickListener`

### Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | `class Builder` |
| [OnTimetableEntrySelectedListener](-on-timetable-entry-selected-listener/index.md) | This callback will be invoked when a specific timetable entry is clicked.`interface OnTimetableEntrySelectedListener` |
| [OnTripKitButtonClickListener](-on-trip-kit-button-click-listener/index.md) | When you provide the Timetable fragment with buttons, this callback will be called when one is clicked.`interface OnTripKitButtonClickListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TimetableFragment()` |

### Properties

| Name | Summary |
|---|---|
| [buttons](buttons.md) | `var buttons: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TripKitButton`](../../com.skedgo.tripkit.ui.model/-trip-kit-button/index.md)`>` |
| [stop](stop.md) | `var stop: `[`ScheduledStop`](../../com.skedgo.tripkit.common.model/-scheduled-stop/index.md)`?` |
| [viewModel](view-model.md) | `lateinit var viewModel: `[`TimetableViewModel`](../-timetable-view-model/index.md) |

### Functions

| Name | Summary |
|---|---|
| [addOnTimetableEntrySelectedListener](add-on-timetable-entry-selected-listener.md) | `fun addOnTimetableEntrySelectedListener(callback: OnTimetableEntrySelectedListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun addOnTimetableEntrySelectedListener(listener: (`[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`, `[`ScheduledStop`](../../com.skedgo.tripkit.common.model/-scheduled-stop/index.md)`, `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onActivityCreated](on-activity-created.md) | `fun onActivityCreated(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onAttach](on-attach.md) | `fun onAttach(context: Context): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onClick](on-click.md) | `fun onClick(p0: View?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreate](on-create.md) | `fun onCreate(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateView](on-create-view.md) | `fun onCreateView(inflater: LayoutInflater, container: ViewGroup?, savedInstanceState: Bundle?): View?` |
| [onDestroy](on-destroy.md) | `fun onDestroy(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onViewCreated](on-view-created.md) | `fun onViewCreated(view: View, savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [selectTime](select-time.md) | `fun selectTime(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOnTripKitButtonClickListener](set-on-trip-kit-button-click-listener.md) | `fun setOnTripKitButtonClickListener(listener: OnTripKitButtonClickListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun setOnTripKitButtonClickListener(listener: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`ScheduledStop`](../../com.skedgo.tripkit.common.model/-scheduled-stop/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
