[tripkit-android](../../index.md) / [com.skedgo.tripkit.alerts](../index.md) / [RealtimeAlertApi](index.md) / [fetchRealtimeAlertsAsync](./fetch-realtime-alerts-async.md)

# fetchRealtimeAlertsAsync

`@GET abstract fun fetchRealtimeAlertsAsync(@Url url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, @Query("region") regionName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): Observable<`[`RealtimeAlertResponse`](../-realtime-alert-response/index.md)`!>!`

See http://skedgo.github.io/tripgo-api/swagger/#!/Transit/get_alerts_transit_json.

### Parameters

`url` - [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!: e.g. https://inflationary-br-rj-riodejaneiro.tripgo.skedgo.com/satapp/alerts/transit.json. The url is a composition of an URL from ``[`Region#getURLs()`](../../com.skedgo.android.common.model/-region/get-u-r-ls.md) and `/alerts/transit.json`.

`regionName` - [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!: Which is ``[`Region#getName()`](../../com.skedgo.android.common.model/-region/get-name.md).