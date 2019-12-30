[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresult](../index.md) / [TripSegmentListFragment](./index.md)

# TripSegmentListFragment

`class TripSegmentListFragment : `[`RxFragment`](../../com.skedgo.tripkit.ui.core.rxlifecyclecomponents/-rx-fragment/index.md)`, OnClickListener`

### Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | `class Builder` |
| [OnTripKitButtonClickListener](-on-trip-kit-button-click-listener/index.md) | `interface OnTripKitButtonClickListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TripSegmentListFragment()` |

### Properties

| Name | Summary |
|---|---|
| [binding](binding.md) | `lateinit var binding: <ERROR CLASS>` |
| [buttons](buttons.md) | `var buttons: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TripKitButton`](../../com.skedgo.tripkit.ui.model/-trip-kit-button/index.md)`>` |
| [errorLogger](error-logger.md) | `lateinit var errorLogger: `[`ErrorLogger`](../../com.skedgo.tripkit.logging/-error-logger/index.md) |
| [viewModel](view-model.md) | `lateinit var viewModel: `[`TripSegmentsViewModel`](../-trip-segments-view-model/index.md) |

### Functions

| Name | Summary |
|---|---|
| [onActivityCreated](on-activity-created.md) | `fun onActivityCreated(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onActivityResult](on-activity-result.md) | `fun onActivityResult(requestCode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, resultCode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, data: Intent?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onAttach](on-attach.md) | `fun onAttach(context: Context): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onClick](on-click.md) | `fun onClick(p0: View?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreate](on-create.md) | `fun onCreate(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateView](on-create-view.md) | `fun onCreateView(inflater: LayoutInflater, container: ViewGroup?, savedInstanceState: Bundle?): View?` |
| [onStart](on-start.md) | `fun onStart(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStop](on-stop.md) | `fun onStop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOnTripKitButtonClickListener](set-on-trip-kit-button-click-listener.md) | `fun setOnTripKitButtonClickListener(callback: OnTripKitButtonClickListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun setOnTripKitButtonClickListener(callback: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`TripGroup`](../../com.skedgo.tripkit.routing/-trip-group/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
