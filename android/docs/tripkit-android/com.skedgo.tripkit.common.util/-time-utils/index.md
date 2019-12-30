[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.util](../index.md) / [TimeUtils](./index.md)

# TimeUtils

`open class TimeUtils`

### Types

| Name | Summary |
|---|---|
| [Duration](-duration/index.md) | According to RFC2445, durations are like this: WEEKS | DAYS [ HOURS [ MINUTES [ SECONDS ] ] ] | HOURS [ MINUTES [ SECONDS ] ] it doesn't specifically, say, but this sort of implies that you can't have 70 seconds.`open class Duration` |
| [InMillis](-in-millis/index.md) | `class InMillis` |
| [InSeconds](-in-seconds/index.md) | `class InSeconds` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TimeUtils()` |

### Properties

| Name | Summary |
|---|---|
| [WHEN_TELEPORTER_EXISTS](-w-h-e-n_-t-e-l-e-p-o-r-t-e-r_-e-x-i-s-t-s.md) | `static var WHEN_TELEPORTER_EXISTS: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |

### Functions

| Name | Summary |
|---|---|
| [getCurrentJulianDay](get-current-julian-day.md) | `open static fun getCurrentJulianDay(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getCurrentMillis](get-current-millis.md) | `open static fun getCurrentMillis(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getDurationInDaysHoursMins](get-duration-in-days-hours-mins.md) | The reason to have days is to prepare for interstate trip`open static fun getDurationInDaysHoursMins(seconds: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getDurationInHoursMins](get-duration-in-hours-mins.md) | `open static fun getDurationInHoursMins(seconds: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getDurationWithDaysInIt](get-duration-with-days-in-it.md) | `open static fun getDurationWithDaysInIt(seconds: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getJulianDay](get-julian-day.md) | `open static fun getJulianDay(t: Time!): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>`open static fun getJulianDay(millis: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getLastSecondOfPreviousDayAsTime](get-last-second-of-previous-day-as-time.md) | `open static fun getLastSecondOfPreviousDayAsTime(startsSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, timeZoneString: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): Time!` |
| [getMillisFrom](get-millis-from.md) | `open static fun getMillisFrom(am_pm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, hour: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, minute: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, sec: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getTimeInDay](get-time-in-day.md) | *`open static fun getTimeInDay(millis: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getTimeZoneDisplayName](get-time-zone-display-name.md) | `open static fun getTimeZoneDisplayName(timezoneId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, timeInSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, locale: `[`Locale`](https://docs.oracle.com/javase/7/docs/api/java/util/Locale.html)`!): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
