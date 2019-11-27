[tripkit-android](../../index.md) / [com.skedgo.tripkit.android](../index.md) / [FetchRegionsService](./index.md)

# FetchRegionsService

`class FetchRegionsService : JobService`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `FetchRegionsService()` |

### Properties

| Name | Summary |
|---|---|
| [runningJob](running-job.md) | `var runningJob: Disposable?` |

### Functions

| Name | Summary |
|---|---|
| [onStartJob](on-start-job.md) | `fun onStartJob(job: JobParameters): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onStopJob](on-stop-job.md) | `fun onStopJob(job: JobParameters?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [scheduleAsync](schedule-async.md) | `fun scheduleAsync(context: Context): Observable<`[`Void`](https://docs.oracle.com/javase/7/docs/api/java/lang/Void.html)`>` |
