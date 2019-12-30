[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database.stops](../index.md) / [StopLocationEntity](./index.md)

# StopLocationEntity

`class StopLocationEntity`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `StopLocationEntity()` |

### Properties

| Name | Summary |
|---|---|
| [address](address.md) | `var address: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [code](code.md) | `lateinit var code: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [lat](lat.md) | `var lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [lng](lng.md) | `var lng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [modeInfo](mode-info.md) | `lateinit var modeInfo: `[`ModeInfoEntity`](../../com.skedgo.tripkit.data.database.locations.bikepods/-mode-info-entity/index.md) |
| [name](name.md) | `lateinit var name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [popularify](popularify.md) | `var popularify: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [services](services.md) | `lateinit var services: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [stopType](stop-type.md) | `lateinit var stopType: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [timeZone](time-zone.md) | `var timeZone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [wheelchairAccessible](wheelchair-accessible.md) | `var wheelchairAccessible: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [toScheduledStop](../to-scheduled-stop.md) | `fun `[`StopLocationEntity`](./index.md)`.toScheduledStop(): `[`ScheduledStop`](../../com.skedgo.tripkit.common.model/-scheduled-stop/index.md) |
