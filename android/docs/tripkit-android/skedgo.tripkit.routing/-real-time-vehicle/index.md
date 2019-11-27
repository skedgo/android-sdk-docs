[tripkit-android](../../index.md) / [skedgo.tripkit.routing](../index.md) / [RealTimeVehicle](./index.md)

# RealTimeVehicle

`open class RealTimeVehicle : Parcelable`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RealTimeVehicle()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`RealTimeVehicle`](./index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [addAlert](add-alert.md) | `open fun addAlert(alert: `[`RealtimeAlert`](../../com.skedgo.android.common.model/-realtime-alert/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getAlerts](get-alerts.md) | `open fun getAlerts(): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`RealtimeAlert`](../../com.skedgo.android.common.model/-realtime-alert/index.md)`!>!` |
| [getArriveAtEndStopTime](get-arrive-at-end-stop-time.md) | `open fun getArriveAtEndStopTime(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getArriveAtStartStopTime](get-arrive-at-start-stop-time.md) | `open fun getArriveAtStartStopTime(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getComponents](get-components.md) | `open fun getComponents(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`VehicleComponent`](../-vehicle-component/index.md)`!>!>?` |
| [getEndStopCode](get-end-stop-code.md) | `open fun getEndStopCode(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getIcon](get-icon.md) | `open fun getIcon(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getId](get-id.md) | `open fun getId(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getLabel](get-label.md) | `open fun getLabel(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getLastUpdateTime](get-last-update-time.md) | `open fun getLastUpdateTime(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getLocation](get-location.md) | `open fun getLocation(): `[`Location`](../../com.skedgo.android.common.model/-location/index.md)`!` |
| [getOccupancy](get-occupancy.md) | `open fun getOccupancy(): `[`Occupancy`](../-occupancy/index.md)`?` |
| [getServiceTripId](get-service-trip-id.md) | `open fun getServiceTripId(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getStartStopCode](get-start-stop-code.md) | `open fun getStartStopCode(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [hasLocationInformation](has-location-information.md) | `open fun hasLocationInformation(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setAlerts](set-alerts.md) | `open fun setAlerts(alerts: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`RealtimeAlert`](../../com.skedgo.android.common.model/-realtime-alert/index.md)`!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setArriveAtEndStopTime](set-arrive-at-end-stop-time.md) | `open fun setArriveAtEndStopTime(arriveAtEndStopTime: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setArriveAtStartStopTime](set-arrive-at-start-stop-time.md) | `open fun setArriveAtStartStopTime(arriveAtStartStopTime: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setComponents](set-components.md) | `open fun setComponents(components: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`VehicleComponent`](../-vehicle-component/index.md)`!>!>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setEndStopCode](set-end-stop-code.md) | `open fun setEndStopCode(endStopCode: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setIcon](set-icon.md) | `open fun setIcon(icon: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setId](set-id.md) | `open fun setId(id: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setLabel](set-label.md) | `open fun setLabel(label: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setLastUpdateTime](set-last-update-time.md) | `open fun setLastUpdateTime(lastUpdateTime: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setLocation](set-location.md) | `open fun setLocation(location: `[`Location`](../../com.skedgo.android.common.model/-location/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOccupancy](set-occupancy.md) | `open fun setOccupancy(occupancy: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceTripId](set-service-trip-id.md) | `open fun setServiceTripId(serviceTripId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStartStopCode](set-start-stop-code.md) | `open fun setStartStopCode(startStopCode: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(dest: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [getAverageOccupancy](../../com.skedgo.tripkit.ui.trip.details.viewmodel/get-average-occupancy.md) | `fun `[`RealTimeVehicle`](./index.md)`.getAverageOccupancy(): `[`Occupancy`](../-occupancy/index.md)`?` |
| [hasSingleVehicleOccupancy](../../com.skedgo.tripkit.ui.trip.details.viewmodel/has-single-vehicle-occupancy.md) | `fun `[`RealTimeVehicle`](./index.md)`.hasSingleVehicleOccupancy(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasVehiclesOccupancy](../../com.skedgo.tripkit.ui.trip.details.viewmodel/has-vehicles-occupancy.md) | `fun `[`RealTimeVehicle`](./index.md)`.hasVehiclesOccupancy(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
