[tripkit-android](../../index.md) / [com.skedgo.geocoding](../index.md) / [GeocodeUtilities](./index.md)

# GeocodeUtilities

`open class GeocodeUtilities`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GeocodeUtilities()` |

### Functions

| Name | Summary |
|---|---|
| [compareInt](compare-int.md) | `open static fun compareInt(x: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, y: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isAbbreviationFor](is-abbreviation-for.md) | `open static fun isAbbreviationFor(abbreviation: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, text: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isSuburb](is-suburb.md) | `open static fun isSuburb(foursquareResult: `[`GCFoursquareResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-foursquare-result-interface/index.md)`!): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [rangedScoreForScore](ranged-score-for-score.md) | `open static fun rangedScoreForScore(score: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, minimum: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, maximum: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [scoreBasedOnDistanceFromCoordinate](score-based-on-distance-from-coordinate.md) | `open static fun scoreBasedOnDistanceFromCoordinate(coordinate: `[`LatLng`](../-lat-lng/index.md)`!, region: `[`GCBoundingBox`](../-g-c-bounding-box/index.md)`!, regionCenter: `[`LatLng`](../-lat-lng/index.md)`!, longDistance: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [scoreBasedOnNameMatchBetweenSearchTerm](score-based-on-name-match-between-search-term.md) | `open static fun scoreBasedOnNameMatchBetweenSearchTerm(searchTerm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, candidate: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [scoreBetweenSearchTerm](score-between-search-term.md) | `open static fun scoreBetweenSearchTerm(target: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, candidate: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [sortByImportance](sort-by-importance.md) | `open static fun <T : `[`GCResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-result-interface/index.md)`!> sortByImportance(scoreResults: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MGAResultInterface`](../../com.skedgo.geocoding.agregator/-m-g-a-result-interface/index.md)`<T>!>!): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MGAResultInterface`](../../com.skedgo.geocoding.agregator/-m-g-a-result-interface/index.md)`<T>!>!` |
| [sortByScore](sort-by-score.md) | `open static fun <T : `[`GCResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-result-interface/index.md)`!> sortByScore(scoreResults: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MGAResultInterface`](../../com.skedgo.geocoding.agregator/-m-g-a-result-interface/index.md)`<T>!>!): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MGAResultInterface`](../../com.skedgo.geocoding.agregator/-m-g-a-result-interface/index.md)`<T>!>!` |
| [stringForScoringOfString](string-for-scoring-of-string.md) | `open static fun stringForScoringOfString(term: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
