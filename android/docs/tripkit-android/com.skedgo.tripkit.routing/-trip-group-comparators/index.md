[tripkit-android](../../index.md) / [com.skedgo.tripkit.routing](../index.md) / [TripGroupComparators](./index.md)

# TripGroupComparators

`class TripGroupComparators`

### Properties

| Name | Summary |
|---|---|
| [ARRIVAL_COMPARATOR_CHAIN](-a-r-r-i-v-a-l_-c-o-m-p-a-r-a-t-o-r_-c-h-a-i-n.md) | To sort routes by leave-after query. `static val ARRIVAL_COMPARATOR_CHAIN: `[`Comparator`](https://docs.oracle.com/javase/7/docs/api/java/util/Comparator.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!` |
| [DEPARTURE_COMPARATOR_CHAIN](-d-e-p-a-r-t-u-r-e_-c-o-m-p-a-r-a-t-o-r_-c-h-a-i-n.md) | To sort routes by arrive-by query. `static val DEPARTURE_COMPARATOR_CHAIN: `[`Comparator`](https://docs.oracle.com/javase/7/docs/api/java/util/Comparator.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!` |
| [DESC_VISIBILITY_COMPARATOR](-d-e-s-c_-v-i-s-i-b-i-l-i-t-y_-c-o-m-p-a-r-a-t-o-r.md) | `static val DESC_VISIBILITY_COMPARATOR: `[`Comparator`](https://docs.oracle.com/javase/7/docs/api/java/util/Comparator.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!` |
| [DISPLAY_TRIP_TRANSFORMER](-d-i-s-p-l-a-y_-t-r-i-p_-t-r-a-n-s-f-o-r-m-e-r.md) | `static val DISPLAY_TRIP_TRANSFORMER: Transformer<`[`TripGroup`](../-trip-group/index.md)`!, `[`Trip`](../-trip/index.md)`!>!` |
| [DURATION_COMPARATOR](-d-u-r-a-t-i-o-n_-c-o-m-p-a-r-a-t-o-r.md) | `static val DURATION_COMPARATOR: `[`Comparator`](https://docs.oracle.com/javase/7/docs/api/java/util/Comparator.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!` |
| [END_TIME_COMPARATOR](-e-n-d_-t-i-m-e_-c-o-m-p-a-r-a-t-o-r.md) | `static val END_TIME_COMPARATOR: `[`Comparator`](https://docs.oracle.com/javase/7/docs/api/java/util/Comparator.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!` |
| [MONEY_COST_COMPARATOR](-m-o-n-e-y_-c-o-s-t_-c-o-m-p-a-r-a-t-o-r.md) | `static val MONEY_COST_COMPARATOR: `[`Comparator`](https://docs.oracle.com/javase/7/docs/api/java/util/Comparator.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!` |
| [START_TIME_COMPARATOR](-s-t-a-r-t_-t-i-m-e_-c-o-m-p-a-r-a-t-o-r.md) | `static val START_TIME_COMPARATOR: `[`Comparator`](https://docs.oracle.com/javase/7/docs/api/java/util/Comparator.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!` |
| [WEIGHTED_SCORE_COMPARATOR](-w-e-i-g-h-t-e-d_-s-c-o-r-e_-c-o-m-p-a-r-a-t-o-r.md) | `static val WEIGHTED_SCORE_COMPARATOR: `[`Comparator`](https://docs.oracle.com/javase/7/docs/api/java/util/Comparator.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [createDurationComparatorChain](create-duration-comparator-chain.md) | `static fun createDurationComparatorChain(willArriveBy: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Comparator`](https://docs.oracle.com/javase/7/docs/api/java/util/Comparator.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!` |
| [createPreferredComparatorChain](create-preferred-comparator-chain.md) | `static fun createPreferredComparatorChain(willArriveBy: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Comparator`](https://docs.oracle.com/javase/7/docs/api/java/util/Comparator.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!` |
| [createPriceComparatorChain](create-price-comparator-chain.md) | `static fun createPriceComparatorChain(willArriveBy: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Comparator`](https://docs.oracle.com/javase/7/docs/api/java/util/Comparator.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!` |
