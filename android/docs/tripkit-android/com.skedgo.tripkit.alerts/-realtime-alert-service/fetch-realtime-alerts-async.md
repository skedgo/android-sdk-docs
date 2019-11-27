[tripkit-android](../../index.md) / [com.skedgo.tripkit.alerts](../index.md) / [RealtimeAlertService](index.md) / [fetchRealtimeAlertsAsync](./fetch-realtime-alerts-async.md)

# fetchRealtimeAlertsAsync

`open fun fetchRealtimeAlertsAsync(@Nullable baseUrls: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>?, @Query("region") regionName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): Observable<`[`RealtimeAlertResponse`](../-realtime-alert-response/index.md)`!>!`

### Parameters

`baseUrls` - [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!&gt;?: Which can be obtained via ``[`Region#getURLs()`](../../com.skedgo.android.common.model/-region/get-u-r-ls.md).

`regionName` - [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!: Which can be obtained via ``[`Region#getName()`](../../com.skedgo.android.common.model/-region/get-name.md).