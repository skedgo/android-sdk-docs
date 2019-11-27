[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map](../index.md) / [BaseMapFragment](./index.md)

# BaseMapFragment

`abstract class BaseMapFragment : `[`RxMapFragment`](../../com.skedgo.tripkit.ui.core.rxlifecyclecomponents/-rx-map-fragment/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BaseMapFragment()` |

### Functions

| Name | Summary |
|---|---|
| [onDestroyView](on-destroy-view.md) | `open fun onDestroyView(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onViewCreated](on-view-created.md) | `open fun onViewCreated(view: View, savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [whenSafeToUseMap](when-safe-to-use-map.md) | A safer point to retrieve [GoogleMap](#) as the callback is invoked after fragment view is measured. This makes it safe to move or animate map with CameraUpdate.`fun whenSafeToUseMap(callback: Consumer<GoogleMap>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [LocationEnhancedMapFragment](../-location-enhanced-map-fragment/index.md) | `open class LocationEnhancedMapFragment : `[`BaseMapFragment`](./index.md) |
