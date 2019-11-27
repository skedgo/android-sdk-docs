[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.servicedetail](../index.md) / [ServiceDetailViewModel](./index.md)

# ServiceDetailViewModel

`class ServiceDetailViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServiceDetailViewModel(context: Context, occupancyViewModel: `[`OccupancyViewModel`](../../com.skedgo.tripkit.ui.trip.details.viewmodel/-occupancy-view-model/index.md)`, serviceViewModelProvider: Provider<`[`ServiceDetailItemViewModel`](../-service-detail-item-view-model/index.md)`>, serviceAlertViewModel: `[`ServiceAlertViewModel`](../../com.skedgo.tripkit.ui.trip.details.viewmodel/-service-alert-view-model/index.md)`, loadServices: `[`LoadServices`](../-load-services/index.md)`, getServiceTitleText: `[`GetServiceTitleText`](../../com.skedgo.tripkit.ui.timetables/-get-service-title-text/index.md)`, getServiceSubTitleText: `[`GetServiceSubTitleText`](../../com.skedgo.tripkit.ui.timetables/-get-service-sub-title-text/index.md)`, getServiceTertiaryText: `[`GetServiceTertiaryText`](../../com.skedgo.tripkit.ui.timetables/-get-service-tertiary-text/index.md)`, getRealtimeText: `[`GetRealtimeText`](../../com.skedgo.tripkit.ui.timetables/-get-realtime-text/index.md)`, errorLogger: `[`ErrorLogger`](../../skedgo.tripkit.logging/-error-logger/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [itemBinding](item-binding.md) | `val itemBinding: ItemBinding<`[`ServiceDetailItemViewModel`](../-service-detail-item-view-model/index.md)`!>` |
| [items](items.md) | `val items: ObservableField<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ServiceDetailItemViewModel`](../-service-detail-item-view-model/index.md)`>>` |
| [occupancyViewModel](occupancy-view-model.md) | `val occupancyViewModel: `[`OccupancyViewModel`](../../com.skedgo.tripkit.ui.trip.details.viewmodel/-occupancy-view-model/index.md) |
| [onItemClicked](on-item-clicked.md) | `val onItemClicked: PublishRelay<`[`ServiceStop`](../../com.skedgo.android.common.model/-service-stop/index.md)`!>` |
| [secondaryText](secondary-text.md) | `val secondaryText: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [secondaryTextColor](secondary-text-color.md) | `val secondaryTextColor: ObservableInt` |
| [serviceAlertViewModel](service-alert-view-model.md) | `val serviceAlertViewModel: `[`ServiceAlertViewModel`](../../com.skedgo.tripkit.ui.trip.details.viewmodel/-service-alert-view-model/index.md) |
| [serviceColor](service-color.md) | `val serviceColor: ObservableInt` |
| [serviceNumber](service-number.md) | `val serviceNumber: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [showOccupancyInfo](show-occupancy-info.md) | `val showOccupancyInfo: ObservableBoolean` |
| [showWheelchairAccessible](show-wheelchair-accessible.md) | `val showWheelchairAccessible: ObservableBoolean` |
| [stationName](station-name.md) | `val stationName: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [stop](stop.md) | `var stop: `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`?` |
| [tertiaryText](tertiary-text.md) | `val tertiaryText: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [timetableEntry](timetable-entry.md) | `var timetableEntry: `[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`?` |
| [wheelchairAccessibleText](wheelchair-accessible-text.md) | `val wheelchairAccessibleText: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [wheelchairIcon](wheelchair-icon.md) | `val wheelchairIcon: ObservableField<Drawable?>` |

### Functions

| Name | Summary |
|---|---|
| [onCleared](on-cleared.md) | This method will be called when this ViewModel is no longer used and will be destroyed.`fun onCleared(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setup](setup.md) | `fun setup(_stop: `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`, _entry: `[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
