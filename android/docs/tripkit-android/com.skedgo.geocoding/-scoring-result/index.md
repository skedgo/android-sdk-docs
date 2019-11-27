[tripkit-android](../../index.md) / [com.skedgo.geocoding](../index.md) / [ScoringResult](./index.md)

# ScoringResult

`open class ScoringResult<T : `[`GCResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-result-interface/index.md)`!> : `[`MGAResultInterface`](../../com.skedgo.geocoding.agregator/-m-g-a-result-interface/index.md)`<T>`

scored single result - without duplicates

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ScoringResult(providerResult: T)` |

### Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | `open fun equals(element: `[`MGAResultInterface`](../../com.skedgo.geocoding.agregator/-m-g-a-result-interface/index.md)`<T>!): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getAddressScore](get-address-score.md) | `open fun getAddressScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getClassRepresentative](get-class-representative.md) | `open fun getClassRepresentative(): `[`MGAResultInterface`](../../com.skedgo.geocoding.agregator/-m-g-a-result-interface/index.md)`<T>!` |
| [getDistanceScore](get-distance-score.md) | `open fun getDistanceScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDuplicates](get-duplicates.md) | `open fun getDuplicates(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MGAResultInterface`](../../com.skedgo.geocoding.agregator/-m-g-a-result-interface/index.md)`<T>!>!` |
| [getNameScore](get-name-score.md) | `open fun getNameScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getPopularityScore](get-popularity-score.md) | `open fun getPopularityScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getResult](get-result.md) | `open fun getResult(): T` |
| [getScore](get-score.md) | `open fun getScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [setAddressScore](set-address-score.md) | `open fun setAddressScore(addressScore: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setDistanceScore](set-distance-score.md) | `open fun setDistanceScore(distanceScore: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setNameScore](set-name-score.md) | `open fun setNameScore(nameScore: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setPopularityScore](set-popularity-score.md) | `open fun setPopularityScore(popularityScore: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setScore](set-score.md) | `open fun setScore(score: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
