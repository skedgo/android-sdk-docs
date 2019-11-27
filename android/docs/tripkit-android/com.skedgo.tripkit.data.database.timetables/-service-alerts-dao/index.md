[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database.timetables](../index.md) / [ServiceAlertsDao](./index.md)

# ServiceAlertsDao

`interface ServiceAlertsDao`

### Functions

| Name | Summary |
|---|---|
| [deleteAlertByService](delete-alert-by-service.md) | `abstract fun deleteAlertByService(alerts: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ServiceAlertsEntity`](../-service-alerts-entity/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getAlertForService](get-alert-for-service.md) | `abstract fun getAlertForService(serviceId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Single<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ServiceAlertsEntity`](../-service-alerts-entity/index.md)`>>` |
| [insertAlerts](insert-alerts.md) | `abstract fun insertAlerts(alerts: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ServiceAlertsEntity`](../-service-alerts-entity/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
