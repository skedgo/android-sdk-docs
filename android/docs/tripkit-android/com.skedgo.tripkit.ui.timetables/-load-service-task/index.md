[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.timetables](../index.md) / [LoadServiceTask](./index.md)

# LoadServiceTask

`open class LoadServiceTask : `[`Callable`](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Callable.html)`<Pair<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`StopInfo`](../../com.skedgo.tripkit.ui.model/-stop-info/index.md)`!>!, `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<ServiceLineInfo!>!>!>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LoadServiceTask(stop: `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`!, cursor: Cursor!)` |

### Functions

| Name | Summary |
|---|---|
| [call](call.md) | `open fun call(): Pair<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`StopInfo`](../../com.skedgo.tripkit.ui.model/-stop-info/index.md)`!>!, `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<ServiceLineInfo!>!>!` |
| [getStopFor](get-stop-for.md) | `open fun getStopFor(code: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`!` |
