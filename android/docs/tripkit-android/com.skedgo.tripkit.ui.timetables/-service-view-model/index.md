[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.timetables](../index.md) / [ServiceViewModel](./index.md)

# ServiceViewModel

`abstract class ServiceViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServiceViewModel()` |

### Properties

| Name | Summary |
|---|---|
| [alpha](alpha.md) | `abstract val alpha: ObservableFloat` |
| [countDownTimeText](count-down-time-text.md) | `abstract val countDownTimeText: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [countDownTimeTextBack](count-down-time-text-back.md) | `abstract val countDownTimeTextBack: ObservableField<Drawable>` |
| [dateTimeZone](date-time-zone.md) | `abstract var dateTimeZone: DateTimeZone` |
| [modeInfo](mode-info.md) | `abstract val modeInfo: ObservableField<`[`ModeInfo`](../../skedgo.tripkit.routing/-mode-info/index.md)`>` |
| [occupancyViewModel](occupancy-view-model.md) | `abstract val occupancyViewModel: `[`OccupancyViewModel`](../../com.skedgo.tripkit.ui.trip.details.viewmodel/-occupancy-view-model/index.md) |
| [onAlertsClick](on-alerts-click.md) | `abstract val onAlertsClick: `[`TapAction`](../../com.skedgo.tripkit.ui.utils/-tap-action/index.md)`<`[`ArrayList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)`<`[`RealtimeAlert`](../../com.skedgo.android.common.model/-realtime-alert/index.md)`>>` |
| [onItemClick](on-item-click.md) | `abstract val onItemClick: `[`TapAction`](../../com.skedgo.tripkit.ui.utils/-tap-action/index.md)`<`[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`>` |
| [secondaryText](secondary-text.md) | `abstract val secondaryText: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [secondaryTextColor](secondary-text-color.md) | `abstract val secondaryTextColor: ObservableInt` |
| [service](service.md) | `abstract var service: `[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md) |
| [serviceAlertViewModel](service-alert-view-model.md) | `abstract val serviceAlertViewModel: `[`ServiceAlertViewModel`](../../com.skedgo.tripkit.ui.trip.details.viewmodel/-service-alert-view-model/index.md) |
| [serviceColor](service-color.md) | `abstract val serviceColor: ObservableInt` |
| [serviceNumber](service-number.md) | `abstract val serviceNumber: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [showOccupancyInfo](show-occupancy-info.md) | `abstract val showOccupancyInfo: ObservableBoolean` |
| [tertiaryText](tertiary-text.md) | `abstract val tertiaryText: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [wheelchairIcon](wheelchair-icon.md) | `abstract val wheelchairIcon: ObservableField<Drawable?>` |
| [wheelchairTint](wheelchair-tint.md) | `abstract val wheelchairTint: ObservableField<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [getRealTimeDeparture](get-real-time-departure.md) | `abstract fun getRealTimeDeparture(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [setService](set-service.md) | `abstract fun setService(_service: `[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`, _dateTimeZone: DateTimeZone): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
