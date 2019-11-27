[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.model](../index.md) / [DeparturesResponse](./index.md)

# DeparturesResponse

`open class DeparturesResponse`

**See Also**
&lt;a href="https://redmine.buzzhives.com/projects/buzzhives/wiki/RealTime_API#DepartureServlet-new-servlet-departuresjson"&gt;departures.json API&lt;/a&gt;

### Types

| Name | Summary |
|---|---|
| [ServicesResponse](-services-response/index.md) | `open class ServicesResponse` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `DeparturesResponse()` |

### Properties

| Name | Summary |
|---|---|
| [embarkationStopList](embarkation-stop-list.md) | `var embarkationStopList: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<ServicesResponse!>!` |
| [error](error.md) | (Optional)`var error: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [hasError](has-error.md) | (Optional)`var hasError: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [stopList](stop-list.md) | (Optional)`var stopList: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [getAlerts](get-alerts.md) | `open fun getAlerts(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`RealtimeAlert`](../../com.skedgo.android.common.model/-realtime-alert/index.md)`!>?` |
| [getParentInfo](get-parent-info.md) | `open fun getParentInfo(): `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`?` |
| [getServiceList](get-service-list.md) | `open fun getServiceList(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TimetableEntry`](../-timetable-entry/index.md)`!>?` |
| [processEmbarkationStopList](process-embarkation-stop-list.md) | Assigns stop code into corresponding service `open fun processEmbarkationStopList(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setAlerts](set-alerts.md) | `open fun setAlerts(alerts: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`RealtimeAlert`](../../com.skedgo.android.common.model/-realtime-alert/index.md)`!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [postProcess](../../com.skedgo.tripkit.ui.timetables.data/post-process.md) | `fun `[`DeparturesResponse`](./index.md)`.postProcess(embarkationStops: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, disembarkationStops: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?): `[`DeparturesResponse`](./index.md) |
