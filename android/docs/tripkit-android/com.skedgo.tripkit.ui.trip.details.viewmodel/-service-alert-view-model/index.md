[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.trip.details.viewmodel](../index.md) / [ServiceAlertViewModel](./index.md)

# ServiceAlertViewModel

`open class ServiceAlertViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServiceAlertViewModel(context: Context)` |

### Properties

| Name | Summary |
|---|---|
| [alertIcon](alert-icon.md) | `val alertIcon: ObservableField<Drawable?>` |
| [hasAlerts](has-alerts.md) | `val hasAlerts: ObservableBoolean` |
| [showAlertsObservable](show-alerts-observable.md) | `open val showAlertsObservable: Observable<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [title](title.md) | `val title: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [onShow](on-show.md) | `fun onShow(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setAlerts](set-alerts.md) | `open fun setAlerts(alerts: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RealtimeAlert`](../../com.skedgo.android.common.model/-realtime-alert/index.md)`>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
