[tripkit-android](../../index.md) / [com.skedgo.geocoding.agregator](../index.md) / [MGAResultInterface](./index.md)

# MGAResultInterface

`interface MGAResultInterface<T : `[`GCResultInterface`](../-g-c-result-interface/index.md)`!> : `[`Serializable`](https://docs.oracle.com/javase/7/docs/api/java/io/Serializable.html)

this class represents a scored result, it could be single or have duplicates

### Functions

| Name | Summary |
|---|---|
| [getAddressScore](get-address-score.md) | `abstract fun getAddressScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getClassRepresentative](get-class-representative.md) | `abstract fun getClassRepresentative(): `[`MGAResultInterface`](./index.md)`<T>!` |
| [getDistanceScore](get-distance-score.md) | `abstract fun getDistanceScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDuplicates](get-duplicates.md) | `abstract fun getDuplicates(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MGAResultInterface`](./index.md)`<T>!>!` |
| [getNameScore](get-name-score.md) | `abstract fun getNameScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getPopularityScore](get-popularity-score.md) | `abstract fun getPopularityScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getResult](get-result.md) | `abstract fun getResult(): T` |
| [getScore](get-score.md) | `abstract fun getScore(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [GroupScoringResult](../../com.skedgo.geocoding/-group-scoring-result/index.md) | scored result with duplicates`open class GroupScoringResult<T : `[`GCResultInterface`](../-g-c-result-interface/index.md)`!> : `[`MGAResultInterface`](./index.md)`<T>` |
| [ScoringResult](../../com.skedgo.geocoding/-scoring-result/index.md) | scored single result - without duplicates`open class ScoringResult<T : `[`GCResultInterface`](../-g-c-result-interface/index.md)`!> : `[`MGAResultInterface`](./index.md)`<T>` |
