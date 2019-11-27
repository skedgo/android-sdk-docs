[tripkit-android](../../index.md) / [skedgo.tripkit.analytics](../index.md) / [MarkTripAsPlannedWithUserInfo](index.md) / [execute](./execute.md)

# execute

`abstract fun execute(plannedUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, userInfo: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>): Completable`

### Parameters

`userInfo` - This parameter is to optionally attach a kind of arbitrary data
which represents user preferences. `userInfo` must be able to be serialized to JSON.