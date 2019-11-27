[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresult](../index.md) / [TripResultPagerFragment](./index.md)

# TripResultPagerFragment

`open class TripResultPagerFragment : `[`RxFragment`](../../com.skedgo.tripkit.ui.core.rxlifecyclecomponents/-rx-fragment/index.md)`, OnPageChangeListener, OnTripKitButtonClickListener`

### Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | `open class Builder` |
| [OnTripKitButtonClickListener](-on-trip-kit-button-click-listener/index.md) | `interface OnTripKitButtonClickListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TripResultPagerFragment()` |

### Functions

| Name | Summary |
|---|---|
| [getCurrentFragment](get-current-fragment.md) | `open fun getCurrentFragment(): Fragment!` |
| [onActivityCreated](on-activity-created.md) | `open fun onActivityCreated(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onAttach](on-attach.md) | `open fun onAttach(context: Context): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateView](on-create-view.md) | `open fun onCreateView(inflater: LayoutInflater, container: ViewGroup?, savedInstanceState: Bundle?): View?` |
| [onPageScrolled](on-page-scrolled.md) | `open fun onPageScrolled(position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, positionOffset: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`, positionOffsetPixels: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onPageScrollStateChanged](on-page-scroll-state-changed.md) | `open fun onPageScrollStateChanged(state: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onPageSelected](on-page-selected.md) | `open fun onPageSelected(position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onPause](on-pause.md) | `open fun onPause(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onResume](on-resume.md) | `open fun onResume(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onSaveInstanceState](on-save-instance-state.md) | `open fun onSaveInstanceState(outState: Bundle): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStart](on-start.md) | `open fun onStart(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStop](on-stop.md) | `open fun onStop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setArgs](set-args.md) | `open fun setArgs(args: PagerFragmentArguments): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setButtons](set-buttons.md) | `open fun setButtons(buttons: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitButton`](../../com.skedgo.tripkit.ui.model/-trip-kit-button/index.md)`!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setMapFragment](set-map-fragment.md) | `open fun setMapFragment(fragment: `[`TripResultMapFragment`](../-trip-result-map-fragment/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOnTripKitButtonClickListener](set-on-trip-kit-button-click-listener.md) | `open fun setOnTripKitButtonClickListener(listener: OnTripKitButtonClickListener!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [tripKitButtonClicked](trip-kit-button-clicked.md) | `open fun tripKitButtonClicked(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, tripGroup: `[`TripGroup`](../../skedgo.tripkit.routing/-trip-group/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
