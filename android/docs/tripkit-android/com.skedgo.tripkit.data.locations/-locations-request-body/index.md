[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.locations](../index.md) / [LocationsRequestBody](./index.md)

# LocationsRequestBody

`class LocationsRequestBody`

### Properties

| Name | Summary |
|---|---|
| [cellIds](cell-ids.md) | `val cellIds: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!` |
| [config](config.md) | `val config: JsonObject!` |
| [existingCells](existing-cells.md) | `val existingCells: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`!>!` |
| [level](level.md) | `val level: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [modes](modes.md) | `val modes: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!` |
| [regionName](region-name.md) | `val regionName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |

### Functions

| Name | Summary |
|---|---|
| [createForNewlyFetching](create-for-newly-fetching.md) | `static fun createForNewlyFetching(region: `[`Region`](../../com.skedgo.android.common.model/-region/index.md)`, cellIds: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>, level: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, config: JsonObject?): `[`LocationsRequestBody`](./index.md)`!` |
| [createForUpdating](create-for-updating.md) | `static fun createForUpdating(region: `[`Region`](../../com.skedgo.android.common.model/-region/index.md)`, existingCells: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`!>, level: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, config: JsonObject?): `[`LocationsRequestBody`](./index.md)`!` |
