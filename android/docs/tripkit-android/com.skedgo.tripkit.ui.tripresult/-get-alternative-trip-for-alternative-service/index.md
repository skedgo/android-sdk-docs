[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresult](../index.md) / [GetAlternativeTripForAlternativeService](./index.md)

# GetAlternativeTripForAlternativeService

`open class GetAlternativeTripForAlternativeService`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GetAlternativeTripForAlternativeService(context: Context, tripGroupRepository: TripGroupRepository, regionService: `[`RegionService`](../../com.skedgo.tripkit.data.regions/-region-service/index.md)`, configRepository: `[`ConfigRepository`](../../skedgo.tripkit.agenda/-config-repository/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [configRepository](config-repository.md) | `val configRepository: `[`ConfigRepository`](../../skedgo.tripkit.agenda/-config-repository/index.md) |
| [context](context.md) | `val context: Context` |
| [regionService](region-service.md) | `val regionService: `[`RegionService`](../../com.skedgo.tripkit.data.regions/-region-service/index.md) |
| [tripGroupRepository](trip-group-repository.md) | `val tripGroupRepository: TripGroupRepository` |

### Functions

| Name | Summary |
|---|---|
| [execute](execute.md) | `open fun execute(trip: `[`Trip`](../../skedgo.tripkit.routing/-trip/index.md)`, tripSegmentId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, selectedService: `[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`): Single<`[`TripGroup`](../../skedgo.tripkit.routing/-trip-group/index.md)`>` |
