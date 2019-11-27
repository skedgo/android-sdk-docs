[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database.stops](../index.md) / [StopLocationDao](./index.md)

# StopLocationDao

`abstract class StopLocationDao`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `StopLocationDao()` |

### Functions

| Name | Summary |
|---|---|
| [getStopsByStopCodes](get-stops-by-stop-codes.md) | `abstract fun getStopsByStopCodes(stopCodes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`StopLocationEntity`](../-stop-location-entity/index.md)`>` |
| [saveAll](save-all.md) | `abstract fun saveAll(stopLocations: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`StopLocationEntity`](../-stop-location-entity/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
