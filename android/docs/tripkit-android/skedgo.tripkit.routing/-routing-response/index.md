[tripkit-android](../../index.md) / [skedgo.tripkit.routing](../index.md) / [RoutingResponse](./index.md)

# RoutingResponse

`open class RoutingResponse`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoutingResponse()` |

### Properties

| Name | Summary |
|---|---|
| [FORMAT_DIRECTION](-f-o-r-m-a-t_-d-i-r-e-c-t-i-o-n.md) | `static val FORMAT_DIRECTION: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [createSegmentTemplateMap](create-segment-template-map.md) | `open fun createSegmentTemplateMap(segmentTemplates: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<JsonObject!>!): SparseArray<JsonObject!>!` |
| [getAlerts](get-alerts.md) | `open fun getAlerts(): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`RealtimeAlert`](../../com.skedgo.android.common.model/-realtime-alert/index.md)`!>!` |
| [getErrorMessage](get-error-message.md) | `open fun getErrorMessage(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getRegionName](get-region-name.md) | `open fun getRegionName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getTripGroupList](get-trip-group-list.md) | `open fun getTripGroupList(): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!` |
| [hasError](has-error.md) | `open fun hasError(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [processDirectionTemplate](process-direction-template.md) | Replaces '' with segment's 'serviceDirection'`open static fun processDirectionTemplate(serviceDirectionNode: JsonPrimitive!, notes: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [processRawData](process-raw-data.md) | `open fun processRawData(resources: Resources!, gson: Gson!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`open fun processRawData(resources: Resources!, gson: Gson!, tripGroups: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!, segmentTemplateMap: SparseArray<JsonObject!>!): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!` |
