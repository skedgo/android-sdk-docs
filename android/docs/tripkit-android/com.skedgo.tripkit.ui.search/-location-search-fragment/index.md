[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.search](../index.md) / [LocationSearchFragment](./index.md)

# LocationSearchFragment

`class LocationSearchFragment : `[`AbstractTripKitFragment`](../../com.skedgo.tripkit.ui.core/-abstract-trip-kit-fragment/index.md)

This is a self-contained location search component which merges search results from both SkedGo's search
results as well as Google Places.

Use it with its Builder:

```
LocationSearchFragment.Builder()
        .withBounds(mMap.projection.visibleRegion.latLngBounds)
        .near(mMap.cameraPosition.target)
        .withHint(getString(R.string.search))
        .allowCurrentLocation(true)
        .allowDropPin()
        .build()
```

### Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | Used to create a new instance of the fragment.`class Builder` |
| [OnCurrentLocationSelectedListener](-on-current-location-selected-listener/index.md) | This callback will be invoked when the user chooses "Current Location"`interface OnCurrentLocationSelectedListener` |
| [OnDropPinSelectedListener](-on-drop-pin-selected-listener/index.md) | This callback will be invoked when the user chooses "Choose on Map"`interface OnDropPinSelectedListener` |
| [OnLocationSelectedListener](-on-location-selected-listener/index.md) | This callback will be invoked when a search result is clicked.`interface OnLocationSelectedListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | This is a self-contained location search component which merges search results from both SkedGo's search results as well as Google Places.`LocationSearchFragment()` |

### Functions

| Name | Summary |
|---|---|
| [setOnCurrentLocationSelectedListener](set-on-current-location-selected-listener.md) | `fun setOnCurrentLocationSelectedListener(callback: OnCurrentLocationSelectedListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun setOnCurrentLocationSelectedListener(listener: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOnDropPinSelectedListener](set-on-drop-pin-selected-listener.md) | `fun setOnDropPinSelectedListener(callback: OnDropPinSelectedListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun setOnDropPinSelectedListener(listener: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOnLocationSelectedListener](set-on-location-selected-listener.md) | `fun setOnLocationSelectedListener(callback: OnLocationSelectedListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun setOnLocationSelectedListener(listener: (`[`Location`](../../com.skedgo.tripkit.common.model/-location/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
