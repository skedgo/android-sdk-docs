[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.dialog](../index.md) / [TimeDatePickerFragment](./index.md)

# TimeDatePickerFragment

`open class TimeDatePickerFragment : DialogFragment, OnClickListener`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TimeDatePickerFragment()` |

### Properties

| Name | Summary |
|---|---|
| [timeRelay](time-relay.md) | `var timeRelay: BehaviorRelay<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [newInstance](new-instance.md) | `open static fun newInstance(timeType: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, initiatorId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, title: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, initialTimeInMillis: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`TimeDatePickerFragment`](./index.md)`!`<br>`open static fun newInstance(timeType: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`TimeDatePickerFragment`](./index.md)`!`<br>`open static fun newInstance(title: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`TimeDatePickerFragment`](./index.md)`!` |
| [onClick](on-click.md) | `open fun onClick(view: View!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreate](on-create.md) | `open fun onCreate(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateDialog](on-create-dialog.md) | `open fun onCreateDialog(savedInstanceState: Bundle?): Dialog` |
