[tripkit-android](../../../index.md) / [com.skedgo.tripkit.ui.dialog](../../index.md) / [TripKitDateTimePickerDialogFragment](../index.md) / [Builder](./index.md)

# Builder

`class Builder`

Used to create a new instance of the fragment.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Used to create a new instance of the fragment.`Builder()` |

### Functions

| Name | Summary |
|---|---|
| [build](build.md) | Builds a new instance of the fragment.`fun build(): `[`TripKitDateTimePickerDialogFragment`](../index.md)`!` |
| [timeMillis](time-millis.md) | The time in milliseconds to display.`fun timeMillis(millis: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): Builder!` |
| [withLocations](with-locations.md) | Sets the departure and arrival location so that the timezones can be supported.`fun withLocations(departureLocation: `[`Location`](../../../com.skedgo.android.common.model/-location/index.md)`?, arrivalLocation: `[`Location`](../../../com.skedgo.android.common.model/-location/index.md)`?): Builder!` |
| [withTimeTag](with-time-tag.md) | Automatically populates the fragment using an existing TimeTag.`fun withTimeTag(tag: `[`TimeTag`](../../../com.skedgo.android.common.model/-time-tag/index.md)`!): Builder!` |
| [withTimeType](with-time-type.md) | Sets a [TimeType] value, which corresponds to: 0 - Leave after 1 - Arrive by`fun withTimeType(timeType: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Builder!` |
| [withTimeZones](with-time-zones.md) | Sets the timezones.`fun withTimeZones(departureTimezone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, arrivalTimezone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): Builder!` |
