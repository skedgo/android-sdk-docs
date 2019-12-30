[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map.home](../index.md) / [StopLoaderArgs](./index.md)

# StopLoaderArgs

`class StopLoaderArgs`

### Properties

| Name | Summary |
|---|---|
| [CELLS_PER_DEGREE](-c-e-l-l-s_-p-e-r_-d-e-g-r-e-e.md) | FIXME: Why 75? This was taken from the iOS impl. If we change into something else rather than 75, it might produce cell ids incompatible with locations.json API.`static val CELLS_PER_DEGREE: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [KEY_CELL_IDS](-k-e-y_-c-e-l-l_-i-d-s.md) | `static val KEY_CELL_IDS: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [KEY_VISIBLE_BOUND](-k-e-y_-v-i-s-i-b-l-e_-b-o-u-n-d.md) | `static val KEY_VISIBLE_BOUND: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [createStopLoaderSelection](create-stop-loader-selection.md) | `static fun createStopLoaderSelection(cellsIdSize: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [createStopLoaderSelectionArgs](create-stop-loader-selection-args.md) | `static fun createStopLoaderSelectionArgs(cellIds: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>, visibleBounds: LatLngBounds): `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!` |
| [getCellIdsByCameraZoom](get-cell-ids-by-camera-zoom.md) | `static fun getCellIdsByCameraZoom(region: `[`Region`](../../com.skedgo.tripkit.common.model/-region/index.md)`, geoPoint: `[`GeoPoint`](../../com.skedgo.tripkit.location/-geo-point/index.md)`, zoom: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`, span: LatLngBounds): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>` |
| [getCellIdsForLoading](get-cell-ids-for-loading.md) | Defines proper cell ids so that the loader can load up stops that should be visible at corresponding level. `static fun getCellIdsForLoading(cellIds: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>, region: `[`Region`](../../com.skedgo.tripkit.common.model/-region/index.md)`): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>` |
| [getCellIdsForLocalLevel](get-cell-ids-for-local-level.md) | `static fun getCellIdsForLocalLevel(geoPoint: `[`GeoPoint`](../../com.skedgo.tripkit.location/-geo-point/index.md)`, span: LatLngBounds): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>`<br>`static fun getCellIdsForLocalLevel(lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, lon: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, latSpan: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, lonSpan: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>` |
| [getCellIdsForRegionalLevel](get-cell-ids-for-regional-level.md) | `static fun getCellIdsForRegionalLevel(region: `[`Region`](../../com.skedgo.tripkit.common.model/-region/index.md)`): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>` |
| [newArgsForStopsLoader](new-args-for-stops-loader.md) | `static fun newArgsForStopsLoader(cellIds: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>, region: `[`Region`](../../com.skedgo.tripkit.common.model/-region/index.md)`, visibleBounds: LatLngBounds): Pair<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!, LatLngBounds!>` |
