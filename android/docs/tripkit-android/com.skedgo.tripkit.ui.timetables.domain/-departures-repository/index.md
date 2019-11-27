[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.timetables.domain](../index.md) / [DeparturesRepository](./index.md)

# DeparturesRepository

`interface DeparturesRepository`

### Functions

| Name | Summary |
|---|---|
| [getTimetableEntries](get-timetable-entries.md) | `abstract fun getTimetableEntries(region: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, embarkationStopCodes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, disembarkationStopCodes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?, timeInSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): Single<`[`DeparturesResponse`](../../com.skedgo.tripkit.ui.model/-departures-response/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [DeparturesRepositoryImpl](../../com.skedgo.tripkit.ui.timetables.data/-departures-repository-impl/index.md) | `class DeparturesRepositoryImpl : `[`DeparturesRepository`](./index.md) |
