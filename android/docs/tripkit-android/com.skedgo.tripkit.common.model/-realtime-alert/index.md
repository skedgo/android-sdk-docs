[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.model](../index.md) / [RealtimeAlert](./index.md)

# RealtimeAlert

`@Immutable @TypeAdapters abstract class RealtimeAlert : Parcelable`

**See Also**
&lt;a href="https://github.com/skedgo/skedgo-java/blob/production/RealTime/src/main/java/com/buzzhives/Realtime/RealtimeAlert.java"&gt;RealtimeAlert&lt;/a&gt;

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RealtimeAlert()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`RealtimeAlert`](./index.md)`!>!` |
| [SEVERITY_ALERT](-s-e-v-e-r-i-t-y_-a-l-e-r-t.md) | `static val SEVERITY_ALERT: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [SEVERITY_WARNING](-s-e-v-e-r-i-t-y_-w-a-r-n-i-n-g.md) | `static val SEVERITY_WARNING: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [alertAction](alert-action.md) | `abstract fun alertAction(): `[`AlertAction`](../-alert-action/index.md)`?` |
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [fromDate](from-date.md) | `open fun fromDate(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [lastUpdated](last-updated.md) | `open fun lastUpdated(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [location](location.md) | `abstract fun location(): `[`Location`](../-location/index.md)`?` |
| [remoteHashCode](remote-hash-code.md) | `abstract fun remoteHashCode(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [remoteIcon](remote-icon.md) | `abstract fun remoteIcon(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [severity](severity.md) | `abstract fun severity(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [text](text.md) | `abstract fun text(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [title](title.md) | `abstract fun title(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [url](url.md) | `abstract fun url(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(out: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
