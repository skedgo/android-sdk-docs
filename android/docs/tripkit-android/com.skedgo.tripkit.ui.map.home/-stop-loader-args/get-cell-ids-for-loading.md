[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map.home](../index.md) / [StopLoaderArgs](index.md) / [getCellIdsForLoading](./get-cell-ids-for-loading.md)

# getCellIdsForLoading

`@NonNull static fun getCellIdsForLoading(@NonNull cellIds: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>, @NonNull region: `[`Region`](../../com.skedgo.android.common.model/-region/index.md)`): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>`

Defines proper cell ids so that the loader can load up stops that should be visible at corresponding level.

 If given cell ids are for the regional level, just return themselves. Why? Because we expect that only parent stops are visible at this level. However, if they are for the local level, should plus the cell ids for the regional level. Why? Because we expect both parent stops and non-parent stops are visible at this level.