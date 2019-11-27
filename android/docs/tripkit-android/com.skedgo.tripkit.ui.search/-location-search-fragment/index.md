[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.search](../index.md) / [LocationSearchFragment](./index.md)

# LocationSearchFragment

`class LocationSearchFragment : `[`AbstractTripKitFragment`](../../com.skedgo.tripkit.ui.core/-abstract-trip-kit-fragment/index.md)

### Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | `class Builder` |
| [OnCurrentLocationSelectedListener](-on-current-location-selected-listener/index.md) | This callback will be invoked when the user chooses "Current Location"`interface OnCurrentLocationSelectedListener` |
| [OnDropPinSelectedListener](-on-drop-pin-selected-listener/index.md) | This callback will be invoked when the user chooses "Choose on Map"`interface OnDropPinSelectedListener` |
| [OnLocationSelectedListener](-on-location-selected-listener/index.md) | This callback will be invoked when a search result is clicked.`interface OnLocationSelectedListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LocationSearchFragment()` |

### Properties

| Name | Summary |
|---|---|
| [bus](bus.md) | `lateinit var bus: Bus` |
| [errorLogger](error-logger.md) | `lateinit var errorLogger: `[`ErrorLogger`](../../skedgo.tripkit.logging/-error-logger/index.md) |
| [viewModel](view-model.md) | `lateinit var viewModel: `[`LocationSearchViewModel`](../-location-search-view-model/index.md) |

### Functions

| Name | Summary |
|---|---|
| [onAttach](on-attach.md) | `fun onAttach(context: Context): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreate](on-create.md) | `fun onCreate(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateView](on-create-view.md) | `fun onCreateView(inflater: LayoutInflater, container: ViewGroup?, savedInstanceState: Bundle?): View?` |
| [onDestroy](on-destroy.md) | `fun onDestroy(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStart](on-start.md) | `fun onStart(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStop](on-stop.md) | `fun onStop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOnCurrentLocationSelectedListener](set-on-current-location-selected-listener.md) | `fun setOnCurrentLocationSelectedListener(callback: OnCurrentLocationSelectedListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun setOnCurrentLocationSelectedListener(listener: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOnDropPinSelectedListener](set-on-drop-pin-selected-listener.md) | `fun setOnDropPinSelectedListener(callback: OnDropPinSelectedListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun setOnDropPinSelectedListener(listener: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOnLocationSelectedListener](set-on-location-selected-listener.md) | `fun setOnLocationSelectedListener(callback: OnLocationSelectedListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun setOnLocationSelectedListener(listener: (`[`Location`](../../com.skedgo.android.common.model/-location/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
