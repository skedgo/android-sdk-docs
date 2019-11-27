[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.regions](../index.md) / [RegionService](./index.md)

# RegionService

`interface RegionService`

### Functions

| Name | Summary |
|---|---|
| [fetchParatransitByRegionAsync](fetch-paratransit-by-region-async.md) | `abstract fun fetchParatransitByRegionAsync(region: `[`Region`](../../com.skedgo.android.common.model/-region/index.md)`): Observable<`[`Paratransit`](../../com.skedgo.tripkit.data.tsp/-paratransit/index.md)`>` |
| [getCitiesAsync](get-cities-async.md) | `abstract fun getCitiesAsync(): Observable<`[`Location`](../../com.skedgo.android.common.model/-location/index.md)`>` |
| [getCitiesByNameAsync](get-cities-by-name-async.md) | `abstract fun getCitiesByNameAsync(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): Observable<`[`Location`](../../com.skedgo.android.common.model/-location/index.md)`>` |
| [getRegionByLocationAsync](get-region-by-location-async.md) | `abstract fun getRegionByLocationAsync(latitude: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, longitude: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): Observable<`[`Region`](../../com.skedgo.android.common.model/-region/index.md)`>`<br>`abstract fun getRegionByLocationAsync(location: `[`Location`](../../com.skedgo.android.common.model/-location/index.md)`?): Observable<`[`Region`](../../com.skedgo.android.common.model/-region/index.md)`>` |
| [getRegionByNameAsync](get-region-by-name-async.md) | `abstract fun getRegionByNameAsync(regionName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`Region`](../../com.skedgo.android.common.model/-region/index.md)`>` |
| [getRegionInfoByRegionAsync](get-region-info-by-region-async.md) | `abstract fun getRegionInfoByRegionAsync(region: `[`Region`](../../com.skedgo.android.common.model/-region/index.md)`): Observable<`[`RegionInfo`](../../com.skedgo.tripkit.data.tsp/-region-info/index.md)`>` |
| [getRegionsAsync](get-regions-async.md) | `abstract fun getRegionsAsync(): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Region`](../../com.skedgo.android.common.model/-region/index.md)`>>` |
| [getTransitModesByRegionAsync](get-transit-modes-by-region-async.md) | `abstract fun getTransitModesByRegionAsync(region: `[`Region`](../../com.skedgo.android.common.model/-region/index.md)`): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ModeInfo`](../../skedgo.tripkit.routing/-mode-info/index.md)`>>` |
| [getTransportModeByIdAsync](get-transport-mode-by-id-async.md) | `abstract fun getTransportModeByIdAsync(modeId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Observable<`[`TransportMode`](../../com.skedgo.android.common.model/-transport-mode/index.md)`>` |
| [getTransportModesAsync](get-transport-modes-async.md) | `abstract fun getTransportModesAsync(): Observable<`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`TransportMode`](../../com.skedgo.android.common.model/-transport-mode/index.md)`>>` |
| [getTransportModesByIdsAsync](get-transport-modes-by-ids-async.md) | `abstract fun getTransportModesByIdsAsync(modeIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TransportMode`](../../com.skedgo.android.common.model/-transport-mode/index.md)`>>` |
| [getTransportModesByLocationAsync](get-transport-modes-by-location-async.md) | `abstract fun getTransportModesByLocationAsync(location: `[`Location`](../../com.skedgo.android.common.model/-location/index.md)`): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TransportMode`](../../com.skedgo.android.common.model/-transport-mode/index.md)`>>` |
| [getTransportModesByRegionAsync](get-transport-modes-by-region-async.md) | `abstract fun getTransportModesByRegionAsync(region: `[`Region`](../../com.skedgo.android.common.model/-region/index.md)`): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TransportMode`](../../com.skedgo.android.common.model/-transport-mode/index.md)`>>` |
| [refreshAsync](refresh-async.md) | `abstract fun refreshAsync(): Completable` |
