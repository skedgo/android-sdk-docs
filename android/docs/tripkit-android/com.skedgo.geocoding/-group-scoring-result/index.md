[tripkit-android](../../index.md) / [com.skedgo.geocoding](../index.md) / [GroupScoringResult](./index.md)

# GroupScoringResult

`open class GroupScoringResult<T : `[`GCResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-result-interface/index.md)`!> : `[`MGAResultInterface`](../../com.skedgo.geocoding.agregator/-m-g-a-result-interface/index.md)`<T>`

scored result with duplicates

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GroupScoringResult()` |

### Functions

| Name | Summary |
|---|---|
| [addDuplicate](add-duplicate.md) | `open fun addDuplicate(scoringResult: `[`ScoringResult`](../-scoring-result/index.md)`<T>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [addDuplicates](add-duplicates.md) | `open fun addDuplicates(scoringResults: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MGAResultInterface`](../../com.skedgo.geocoding.agregator/-m-g-a-result-interface/index.md)`<T>!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getAddressScore](get-address-score.md) | `open fun getAddressScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getClassRepresentative](get-class-representative.md) | `open fun getClassRepresentative(): `[`MGAResultInterface`](../../com.skedgo.geocoding.agregator/-m-g-a-result-interface/index.md)`<T>!` |
| [getDistanceScore](get-distance-score.md) | `open fun getDistanceScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDuplicates](get-duplicates.md) | `open fun getDuplicates(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MGAResultInterface`](../../com.skedgo.geocoding.agregator/-m-g-a-result-interface/index.md)`<T>!>!` |
| [getNameScore](get-name-score.md) | `open fun getNameScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getPopularityScore](get-popularity-score.md) | `open fun getPopularityScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getResult](get-result.md) | `open fun getResult(): T` |
| [getScore](get-score.md) | `open fun getScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getScoringResult](get-scoring-result.md) | `open fun getScoringResult(): `[`ScoringResult`](../-scoring-result/index.md)`<T>!` |
