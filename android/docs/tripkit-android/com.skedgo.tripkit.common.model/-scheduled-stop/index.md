[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.model](../index.md) / [ScheduledStop](./index.md)

# ScheduledStop

`open class ScheduledStop : `[`Location`](../-location/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ScheduledStop()`<br>`ScheduledStop(location: `[`Location`](../-location/index.md)`!)` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`ScheduledStop`](./index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [convertStopTypeToTransportModeIcon](convert-stop-type-to-transport-mode-icon.md) | `open static fun convertStopTypeToTransportModeIcon(type: `[`StopType`](../-stop-type/index.md)`!): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [convertStopTypeToVehicleMode](convert-stop-type-to-vehicle-mode.md) | `open static fun convertStopTypeToVehicleMode(type: `[`StopType`](../-stop-type/index.md)`!): `[`VehicleMode`](../../com.skedgo.tripkit.routing/-vehicle-mode/index.md)`!` |
| [equals](equals.md) | `open fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [fillFrom](fill-from.md) | `open fun fillFrom(location: `[`Location`](../-location/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getAlertHashCodes](get-alert-hash-codes.md) | `open fun getAlertHashCodes(): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`!>?` |
| [getChildren](get-children.md) | `open fun getChildren(): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`ScheduledStop`](./index.md)`!>!` |
| [getCode](get-code.md) | `open fun getCode(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getCurrentFilter](get-current-filter.md) | `open fun getCurrentFilter(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getEmbarkationStopCode](get-embarkation-stop-code.md) | `open fun getEmbarkationStopCode(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!` |
| [getLocationType](get-location-type.md) | `open fun getLocationType(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getModeInfo](get-mode-info.md) | `open fun getModeInfo(): `[`ModeInfo`](../../com.skedgo.tripkit.routing/-mode-info/index.md)`!` |
| [getParentId](get-parent-id.md) | `open fun getParentId(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getServices](get-services.md) | `open fun getServices(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getShortName](get-short-name.md) | `open fun getShortName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getStopId](get-stop-id.md) | `open fun getStopId(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getType](get-type.md) | `open fun getType(): `[`StopType`](../-stop-type/index.md)`!` |
| [getWheelchairAccessible](get-wheelchair-accessible.md) | `open fun getWheelchairAccessible(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [hasChildren](has-children.md) | `open fun hasChildren(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | `open fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isParent](is-parent.md) | Alias of ``[`#hasChildren()`](has-children.md). If a stop has children, it's a parent stop.`open fun isParent(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setAlertHashCodes](set-alert-hash-codes.md) | `open fun setAlertHashCodes(alertHashCodes: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`!>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setChildren](set-children.md) | `open fun setChildren(children: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`ScheduledStop`](./index.md)`!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setCode](set-code.md) | `open fun setCode(code: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setCurrentFilter](set-current-filter.md) | `open fun setCurrentFilter(filter: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setModeInfo](set-mode-info.md) | `open fun setModeInfo(modeInfo: `[`ModeInfo`](../../com.skedgo.tripkit.routing/-mode-info/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setParent](set-parent.md) | `open fun setParent(parent: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServices](set-services.md) | `open fun setServices(services: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setShortName](set-short-name.md) | `open fun setShortName(shortName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStopId](set-stop-id.md) | `open fun setStopId(stopId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setType](set-type.md) | `open fun setType(type: `[`StopType`](../-stop-type/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setWheelchairAccessible](set-wheelchair-accessible.md) | `open fun setWheelchairAccessible(wheelchairAccessible: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(out: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [createStopMarkerOptions](../../com.skedgo.tripkit.ui.map/create-stop-marker-options.md) | `fun `[`ScheduledStop`](./index.md)`.createStopMarkerOptions(): Single<MarkerOptions>` |
| [getStopDisplayName](../../com.skedgo.tripkit.ui.map/get-stop-display-name.md) | `fun `[`ScheduledStop`](./index.md)`.getStopDisplayName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [toEntity](../../com.skedgo.tripkit.data.database.stops/to-entity.md) | `fun `[`ScheduledStop`](./index.md)`.toEntity(): `[`StopLocationEntity`](../../com.skedgo.tripkit.data.database.stops/-stop-location-entity/index.md) |
