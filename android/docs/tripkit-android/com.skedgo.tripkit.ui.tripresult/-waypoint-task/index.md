[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresult](../index.md) / [WaypointTask](./index.md)

# WaypointTask

`open class WaypointTask : SingleOnSubscribe<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripGroup`](../../skedgo.tripkit.routing/-trip-group/index.md)`!>!>`

https://redmine.buzzhives.com/projects/buzzhives/wiki/Routing_API#Trips-from-waypoint

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `WaypointTask(context: Context, configCreator: `[`ConfigRepository`](../../skedgo.tripkit.agenda/-config-repository/index.md)`, param: `[`WayPointTaskParam`](../-way-point-task-param/index.md)`!)` |

### Properties

| Name | Summary |
|---|---|
| [FORMAT_COORDINATES](-f-o-r-m-a-t_-c-o-o-r-d-i-n-a-t-e-s.md) | `static val FORMAT_COORDINATES: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [KEY_CONFIG](-k-e-y_-c-o-n-f-i-g.md) | `static val KEY_CONFIG: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [KEY_END](-k-e-y_-e-n-d.md) | `static val KEY_END: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [KEY_END_TIME](-k-e-y_-e-n-d_-t-i-m-e.md) | `static val KEY_END_TIME: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [KEY_MODES](-k-e-y_-m-o-d-e-s.md) | `static val KEY_MODES: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [KEY_OPERATOR](-k-e-y_-o-p-e-r-a-t-o-r.md) | `static val KEY_OPERATOR: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [KEY_REGION](-k-e-y_-r-e-g-i-o-n.md) | `static val KEY_REGION: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [KEY_SEGMENTS](-k-e-y_-s-e-g-m-e-n-t-s.md) | `static val KEY_SEGMENTS: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [KEY_SERVICE_TRIP_ID](-k-e-y_-s-e-r-v-i-c-e_-t-r-i-p_-i-d.md) | `static val KEY_SERVICE_TRIP_ID: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [KEY_START](-k-e-y_-s-t-a-r-t.md) | `static val KEY_START: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [KEY_START_TIME](-k-e-y_-s-t-a-r-t_-t-i-m-e.md) | `static val KEY_START_TIME: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [subscribe](subscribe.md) | `open fun subscribe(singleSubscriber: SingleEmitter<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripGroup`](../../skedgo.tripkit.routing/-trip-group/index.md)`!>!>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
