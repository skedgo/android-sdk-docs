[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.timetables](../index.md) / [ServiceRepositoryImpl](./index.md)

# ServiceRepositoryImpl

`class ServiceRepositoryImpl : `[`ServiceRepository`](../-service-repository/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServiceRepositoryImpl(context: Context, fetchService: `[`FetchService`](../-fetch-service/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [fetchServices](fetch-services.md) | `fun fetchServices(service: `[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`, stop: `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`): Completable` |
| [loadServices](load-services.md) | `fun loadServices(service: `[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`, stop: `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`): Single<Pair<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`StopInfo`](../../com.skedgo.tripkit.ui.model/-stop-info/index.md)`>, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<ServiceLineInfo>>>` |
