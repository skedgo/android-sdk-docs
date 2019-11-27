[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database.locations.carparks](../index.md) / [CarParkDao](./index.md)

# CarParkDao

`interface CarParkDao`

### Functions

| Name | Summary |
|---|---|
| [getByCellIds](get-by-cell-ids.md) | `abstract fun getByCellIds(ids: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): Flowable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CarParkLocationEntity`](../-car-park-location-entity/index.md)`>>` |
| [getOpeningTimesByCarParkId](get-opening-times-by-car-park-id.md) | `abstract fun getOpeningTimesByCarParkId(carParkId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OpeningTimeResult`](../-opening-time-result/index.md)`>` |
| [getPricingEntriesByPricingTableId](get-pricing-entries-by-pricing-table-id.md) | `abstract fun getPricingEntriesByPricingTableId(pricingTableId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`PricingEntryEntity`](../-pricing-entry-entity/index.md)`>` |
| [getPricingTablesByCarParkId](get-pricing-tables-by-car-park-id.md) | `abstract fun getPricingTablesByCarParkId(carParkId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`PricingTableEntity`](../-pricing-table-entity/index.md)`>` |
| [saveAll](save-all.md) | `abstract fun saveAll(carParks: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CarParkLocationEntity`](../-car-park-location-entity/index.md)`>, openingDays: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OpeningDayEntity`](../-opening-day-entity/index.md)`>, openingTimes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OpeningTimeEntity`](../-opening-time-entity/index.md)`>, pricingTables: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`PricingTableEntity`](../-pricing-table-entity/index.md)`>, pricingEntries: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`PricingEntryEntity`](../-pricing-entry-entity/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
