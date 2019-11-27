[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.timetables](../index.md) / [TimetableViewModel](./index.md)

# TimetableViewModel

`class TimetableViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TimetableViewModel(realTimeChoreographer: `[`RealTimeChoreographer`](../../com.skedgo.tripkit.ui.realtime/-real-time-choreographer/index.md)`, fetchAndLoadTimetable: `[`FetchAndLoadTimetable`](../-fetch-and-load-timetable/index.md)`, serviceViewModelProvider: Provider<`[`ServiceViewModel`](../-service-view-model/index.md)`>, regionService: `[`RegionService`](../../com.skedgo.tripkit.data.regions/-region-service/index.md)`, getNow: `[`GetNow`](../../com.skedgo.tripkit.time/-get-now/index.md)`, resources: Resources)` |

### Properties

| Name | Summary |
|---|---|
| [downloadTimetable](download-timetable.md) | `val downloadTimetable: PublishRelay<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [filter](filter.md) | `val filter: BehaviorRelay<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [itemBinding](item-binding.md) | `val itemBinding: ItemBinding<`[`ServiceViewModel`](../-service-view-model/index.md)`!>` |
| [minStartTime](min-start-time.md) | `val minStartTime: Observable<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`!>!` |
| [onAlertClicks](on-alert-clicks.md) | `val onAlertClicks: Observable<`[`ArrayList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)`<`[`RealtimeAlert`](../../com.skedgo.android.common.model/-realtime-alert/index.md)`>>` |
| [onDateChanged](on-date-changed.md) | `val onDateChanged: PublishRelay<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [onServiceClick](on-service-click.md) | `val onServiceClick: Observable<`[`Triple`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-triple/index.html)`<`[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`, `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`, `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`!>!>!` |
| [scrollToNow](scroll-to-now.md) | `val scrollToNow: PublishRelay<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [serviceItemBinding](service-item-binding.md) | `val serviceItemBinding: ItemBinding<`[`TimetableHeaderLineItem`](../../com.skedgo.tripkit.ui.model/-timetable-header-line-item/index.md)`!>` |
| [serviceNumbers](service-numbers.md) | `val serviceNumbers: ObservableField<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TimetableHeaderLineItem`](../../com.skedgo.tripkit.ui.model/-timetable-header-line-item/index.md)`>>` |
| [services](services.md) | `val services: ObservableField<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ServiceViewModel`](../-service-view-model/index.md)`>>` |
| [showError](show-error.md) | `val showError: PublishRelay<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [showLoading](show-loading.md) | `val showLoading: ObservableBoolean` |
| [stationName](station-name.md) | `val stationName: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [stationType](station-type.md) | `val stationType: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [stop](stop.md) | `var stop: BehaviorRelay<`[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [downloadMoreTimetableAsync](download-more-timetable-async.md) | `fun downloadMoreTimetableAsync(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getFirstNowPosition](get-first-now-position.md) | `fun getFirstNowPosition(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [onCleared](on-cleared.md) | This method will be called when this ViewModel is no longer used and will be destroyed.`fun onCleared(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setText](set-text.md) | `fun setText(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
