[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresults](../index.md) / [TripResultListFragment](./index.md)

# TripResultListFragment

`class TripResultListFragment : `[`AbstractTripKitFragment`](../../com.skedgo.tripkit.ui.core/-abstract-trip-kit-fragment/index.md)

### Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | `class Builder` |
| [OnLocationClickListener](-on-location-click-listener/index.md) | `interface OnLocationClickListener` |
| [OnTripSelectedListener](-on-trip-selected-listener/index.md) | This callback will be invoked when a search result is clicked.`interface OnTripSelectedListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TripResultListFragment()` |

### Properties

| Name | Summary |
|---|---|
| [binding](binding.md) | `lateinit var binding: <ERROR CLASS>` |
| [shouldShowMoreButton](should-show-more-button.md) | `var shouldShowMoreButton: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [viewModel](view-model.md) | `lateinit var viewModel: `[`TripResultListViewModel`](../-trip-result-list-view-model/index.md) |

### Functions

| Name | Summary |
|---|---|
| [onActivityCreated](on-activity-created.md) | `fun onActivityCreated(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onAttach](on-attach.md) | `fun onAttach(context: Context): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateView](on-create-view.md) | `fun onCreateView(inflater: LayoutInflater, container: ViewGroup?, savedInstanceState: Bundle?): View?` |
| [onViewCreated](on-view-created.md) | `fun onViewCreated(view: View, savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [query](query.md) | `fun query(): `[`Query`](../../com.skedgo.android.common.model/-query/index.md) |
| [setOnLocationClickListener](set-on-location-click-listener.md) | `fun setOnLocationClickListener(listener: OnLocationClickListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun setOnLocationClickListener(startLocationClicked: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, destinationLocationClicked: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOnTripSelectedListener](set-on-trip-selected-listener.md) | `fun setOnTripSelectedListener(callback: OnTripSelectedListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun setOnTripSelectedListener(callback: (ViewTrip) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setQuery](set-query.md) | `fun setQuery(query: `[`Query`](../../com.skedgo.android.common.model/-query/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
