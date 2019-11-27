[tripkit-android](../../index.md) / [com.skedgo.tripkit](../index.md) / [TripPreferences](./index.md)

# TripPreferences

`interface TripPreferences`

### Functions

| Name | Summary |
|---|---|
| [isConcessionPricingPreferred](is-concession-pricing-preferred.md) | This option should be used when ``[`RegionInfo#supportsConcessionPricing()`](../../com.skedgo.tripkit.data.tsp/-region-info/supports-concession-pricing.md) is true.`abstract fun isConcessionPricingPreferred(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isWheelchairPreferred](is-wheelchair-preferred.md) | This option should be used when ``[`RegionInfo#transitWheelchairAccessibility()`](../../com.skedgo.tripkit.data.tsp/-region-info/transit-wheelchair-accessibility.md) is true.`abstract fun isWheelchairPreferred(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setConcessionPricingPreferred](set-concession-pricing-preferred.md) | `abstract fun setConcessionPricingPreferred(isConcessionPricingPreferred: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setWheelchairPreferred](set-wheelchair-preferred.md) | `abstract fun setWheelchairPreferred(isWheelchairPreferred: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [whenConcessionPricingPreferenceChanges](when-concession-pricing-preference-changes.md) | `abstract fun whenConcessionPricingPreferenceChanges(): Observable<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`!>!` |
| [whenWheelchairPreferenceChanges](when-wheelchair-preference-changes.md) | `abstract fun whenWheelchairPreferenceChanges(): Observable<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`!>!` |

### Inheritors

| Name | Summary |
|---|---|
| [DefaultTripPreferences](../-default-trip-preferences/index.md) | `class DefaultTripPreferences : `[`TripPreferences`](./index.md) |
