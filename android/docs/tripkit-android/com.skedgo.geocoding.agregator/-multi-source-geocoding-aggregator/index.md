[tripkit-android](../../index.md) / [com.skedgo.geocoding.agregator](../index.md) / [MultiSourceGeocodingAggregator](./index.md)

# MultiSourceGeocodingAggregator

`open class MultiSourceGeocodingAggregator<T : `[`GCResultInterface`](../-g-c-result-interface/index.md)`!>`

Scoring formulas Favourites: max(title, address) Search history: max(title, address) Regions: distance Address book: (title + address) / 2 Calendar: (title + address) / 2 SkedGo transit stops: popularity -&gt; ((min(popularity, GOOD_SCORE)) / (GOOD_SCORE / 100)) * 2 SkedGo others: title Google: (max(title, address) * 3 + distance) / 4 Google Autocomplete: (title * 3) / 4 Foursquare: ((title * 3 + distance) / 4) * suburb Title score: score based on input string against the title of the result Address score: score based on input string against address of the result Distance score: score based on distance to center or provided region Suburb score: bonus score if result is a suburb Popularity score: score based on popularity of result as determined by server

### Functions

| Name | Summary |
|---|---|
| [aggregate](aggregate.md) | `open fun aggregate(userQuery: `[`GCQueryInterface`](../-g-c-query-interface/index.md)`!, providersResults: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<T>!>!): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MGAResultInterface`](../-m-g-a-result-interface/index.md)`<T>!>!` |
| [flattenAggregate](flatten-aggregate.md) | `open fun flattenAggregate(userQuery: `[`GCQueryInterface`](../-g-c-query-interface/index.md)`!, providersResults: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<T>!>!): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`GCResultInterface`](../-g-c-result-interface/index.md)`!>!` |
| [getInstance](get-instance.md) | `open static fun getInstance(): `[`MultiSourceGeocodingAggregator`](./index.md)`<`[`GCResultInterface`](../-g-c-result-interface/index.md)`!>!` |
