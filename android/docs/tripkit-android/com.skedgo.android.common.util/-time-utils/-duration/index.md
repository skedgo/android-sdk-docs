[tripkit-android](../../../index.md) / [com.skedgo.android.common.util](../../index.md) / [TimeUtils](../index.md) / [Duration](./index.md)

# Duration

`open class Duration`

According to RFC2445, durations are like this: WEEKS | DAYS [ HOURS [ MINUTES [ SECONDS ] ] ] | HOURS [ MINUTES [ SECONDS ] ] it doesn't specifically, say, but this sort of implies that you can't have 70 seconds.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Duration()` |

### Properties

| Name | Summary |
|---|---|
| [days](days.md) | `var days: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [hours](hours.md) | `var hours: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [minutes](minutes.md) | `var minutes: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [seconds](seconds.md) | `var seconds: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [sign](sign.md) | `var sign: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [weeks](weeks.md) | `var weeks: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Functions

| Name | Summary |
|---|---|
| [getMillis](get-millis.md) | `open fun getMillis(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [parse](parse.md) | Parse according to RFC2445 ss4.3.6. (It's actually a little loose with its parsing, for better or for worse)`open fun parse(str: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
