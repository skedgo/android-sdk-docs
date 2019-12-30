[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.locations](../index.md) / [StopsFetcher](./index.md)

# StopsFetcher

`open class StopsFetcher`

### Types

| Name | Summary |
|---|---|
| [ICellsLoader](-i-cells-loader/index.md) | `interface ICellsLoader` |
| [ICellsPersistor](-i-cells-persistor/index.md) | `interface ICellsPersistor` |
| [IStopsPersistor](-i-stops-persistor/index.md) | `interface IStopsPersistor` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `StopsFetcher(api: `[`LocationsApi`](../-locations-api/index.md)`, cellsLoader: ICellsLoader, cellsPersistor: ICellsPersistor, stopsPersistor: IStopsPersistor, configCreator: `[`ConfigRepository`](../../com.skedgo.tripkit.agenda/-config-repository/index.md)`, bikePodRepository: `[`BikePodRepository`](../../com.skedgo.tripkit.data.database.locations.bikepods/-bike-pod-repository/index.md)`, carParkPersistor: `[`CarParkPersistor`](../../com.skedgo.tripkit.data.database.locations.carparks/-car-park-persistor/index.md)`, onStreetParkingPersistor: `[`OnStreetParkingPersistor`](../../com.skedgo.tripkit.data.database.locations.onstreetparking/-on-street-parking-persistor/index.md)`, carParkMapper: `[`CarParkMapper`](../../com.skedgo.tripkit.data.database.locations.carparks/-car-park-mapper/index.md)`, carPodMapper: `[`CarPodMapper`](../../com.skedgo.tripkit.data.database.locations.carpods/-car-pod-mapper/index.md)`, onStreetParkingMapper: `[`OnStreetParkingMapper`](../../com.skedgo.tripkit.data.database.locations.onstreetparking/-on-street-parking-mapper/index.md)`, carPodRepository: `[`CarPodRepository`](../../com.skedgo.tripkit.data.database.locations.carpods/-car-pod-repository/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [fetchAsync](fetch-async.md) | `open fun fetchAsync(cellIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, region: `[`Region`](../../com.skedgo.tripkit.common.model/-region/index.md)`, level: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<Group>>` |
