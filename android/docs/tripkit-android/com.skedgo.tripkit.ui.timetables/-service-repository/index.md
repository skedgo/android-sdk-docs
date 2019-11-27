[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.timetables](../index.md) / [ServiceRepository](./index.md)

# ServiceRepository

`interface ServiceRepository`

### Functions

| Name | Summary |
|---|---|
| [fetchServices](fetch-services.md) | `abstract fun fetchServices(service: `[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`, stop: `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`): Completable` |
| [loadServices](load-services.md) | `abstract fun loadServices(service: `[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`, stop: `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`): Single<Pair<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`StopInfo`](../../com.skedgo.tripkit.ui.model/-stop-info/index.md)`>, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<ServiceLineInfo>>>` |

### Inheritors

| Name | Summary |
|---|---|
| [ServiceRepositoryImpl](../-service-repository-impl/index.md) | `class ServiceRepositoryImpl : `[`ServiceRepository`](./index.md) |
