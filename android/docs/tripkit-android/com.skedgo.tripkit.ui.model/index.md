[tripkit-android](../index.md) / [com.skedgo.tripkit.ui.model](./index.md)

## Package com.skedgo.tripkit.ui.model

### Types

| Name | Summary |
|---|---|
| [DeparturesResponse](-departures-response/index.md) | `open class DeparturesResponse` |
| [StopInfo](-stop-info/index.md) | Thuy's remark: This should have been ``[`ServiceStop`](../com.skedgo.tripkit.common.model/-service-stop/index.md). We parse network response into ServiceStops, then persist them into SQLite database. However, when loading, we use such ``[`StopInfo`](-stop-info/index.md) to indicate service' stops.`open class StopInfo` |
| [TimetableEntry](-timetable-entry/index.md) | (Aka Service)`open class TimetableEntry : Parcelable, `[`IRealTimeElement`](../com.skedgo.tripkit.common.agenda/-i-real-time-element/index.md)`, `[`ITimeRange`](../com.skedgo.tripkit.common.model/-i-time-range/index.md)`, `[`WheelchairAccessible`](../com.skedgo.tripkit.common.model/-wheelchair-accessible/index.md) |
| [TimetableHeaderLineItem](-timetable-header-line-item/index.md) | `open class TimetableHeaderLineItem` |
| [TripKitButton](-trip-kit-button/index.md) | `class TripKitButton` |
