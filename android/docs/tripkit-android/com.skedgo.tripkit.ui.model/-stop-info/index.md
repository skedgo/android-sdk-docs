[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.model](../index.md) / [StopInfo](./index.md)

# StopInfo

`open class StopInfo`

Thuy's remark: This should have been ``[`ServiceStop`](../../com.skedgo.android.common.model/-service-stop/index.md). We parse network response into ServiceStops, then persist them into SQLite database. However, when loading, we use such ``[`StopInfo`](./index.md) to indicate service' stops.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `StopInfo(id: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, realTimeStatus: `[`RealTimeStatus`](../../com.skedgo.android.common.model/-real-time-status/index.md)`!, sortByArrive: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, stop: `[`ServiceStop`](../../com.skedgo.android.common.model/-service-stop/index.md)`!, serviceColor: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, travelled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [id](id.md) | `val id: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [realTimeStatus](real-time-status.md) | `val realTimeStatus: `[`RealTimeStatus`](../../com.skedgo.android.common.model/-real-time-status/index.md)`!` |
| [serviceColor](service-color.md) | `val serviceColor: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [sortByArrive](sort-by-arrive.md) | `val sortByArrive: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [stop](stop.md) | `val stop: `[`ServiceStop`](../../com.skedgo.android.common.model/-service-stop/index.md)`!` |
| [travelled](travelled.md) | `var travelled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
