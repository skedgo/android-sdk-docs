[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database.locations.carparks](../index.md) / [CarParkPersistor](./index.md)

# CarParkPersistor

`open class CarParkPersistor`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `CarParkPersistor(tripKitDatabase: `[`TripKitDatabase`](../../com.skedgo.tripkit.data.database/-trip-kit-database/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [tripKitDatabase](trip-kit-database.md) | `val tripKitDatabase: `[`TripKitDatabase`](../../com.skedgo.tripkit.data.database/-trip-kit-database/index.md) |

### Functions

| Name | Summary |
|---|---|
| [saveCarParks](save-car-parks.md) | `fun saveCarParks(carParkEntity: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Triple`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-triple/index.html)`<`[`CarParkLocationEntity`](../-car-park-location-entity/index.md)`, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`OpeningDayEntity`](../-opening-day-entity/index.md)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OpeningTimeEntity`](../-opening-time-entity/index.md)`>>, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`PricingTableEntity`](../-pricing-table-entity/index.md)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`PricingEntryEntity`](../-pricing-entry-entity/index.md)`>>>>): Completable` |
