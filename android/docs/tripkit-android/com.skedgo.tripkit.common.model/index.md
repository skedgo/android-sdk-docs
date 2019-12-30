[tripkit-android](../index.md) / [com.skedgo.tripkit.common.model](./index.md)

## Package com.skedgo.tripkit.common.model

### Types

| Name | Summary |
|---|---|
| [AlertAction](-alert-action/index.md) | `abstract class AlertAction : Parcelable` |
| [Booking](-booking/index.md) | `abstract class Booking` |
| [BookingConfirmation](-booking-confirmation/index.md) | `abstract class BookingConfirmation : Parcelable` |
| [BookingConfirmationAction](-booking-confirmation-action/index.md) | `abstract class BookingConfirmationAction : Parcelable` |
| [BookingConfirmationImage](-booking-confirmation-image/index.md) | `abstract class BookingConfirmationImage : Parcelable` |
| [BookingConfirmationPurchase](-booking-confirmation-purchase/index.md) | `abstract class BookingConfirmationPurchase : Parcelable` |
| [BookingConfirmationStatus](-booking-confirmation-status/index.md) | `abstract class BookingConfirmationStatus : Parcelable` |
| [BookingProvider](-booking-provider/index.md) | `abstract class BookingProvider : Parcelable` |
| [BookingSource](-booking-source/index.md) | `abstract class BookingSource : Parcelable` |
| [ITimeRange](-i-time-range/index.md) | `interface ITimeRange` |
| [Location](-location/index.md) | `open class Location : Parcelable` |
| [PurchaseBrand](-purchase-brand/index.md) | `abstract class PurchaseBrand : Parcelable` |
| [Query](-query/index.md) | Represents a query to find routes from A to B. Note that, to avoid `TransactionTooLargeException`, it's discouraged to pass any instance of `Query` to an `Intent` or a `Bundle`. The `Parcelable` is subject to deletion at anytime.`open class Query : Parcelable` |
| [RealtimeAlert](-realtime-alert/index.md) | `abstract class RealtimeAlert : Parcelable` |
| [RealtimeAlerts](-realtime-alerts/index.md) | `class RealtimeAlerts` |
| [RealTimeStatus](-real-time-status/index.md) | `class RealTimeStatus` |
| [Region](-region/index.md) | `open class Region : Parcelable` |
| [Regions](-regions/index.md) | `class Regions` |
| [RegionsResponse](-regions-response/index.md) | `open class RegionsResponse` |
| [ScheduledStop](-scheduled-stop/index.md) | `open class ScheduledStop : `[`Location`](-location/index.md) |
| [ServiceStop](-service-stop/index.md) | Represents a future stop of a service in a trip.`open class ServiceStop : `[`Location`](-location/index.md)`, `[`WheelchairAccessible`](-wheelchair-accessible/index.md) |
| [StopType](-stop-type/index.md) | `class StopType` |
| [Street](-street/index.md) | `abstract class Street : Parcelable` |
| [TimeTag](-time-tag/index.md) | A TimeTag encapsulates a departure or arrival time, including a dynamic time of "now".`open class TimeTag : Parcelable` |
| [TransportMode](-transport-mode/index.md) | `open class TransportMode` |
| [Units](-units/index.md) | `class Units` |
| [WheelchairAccessible](-wheelchair-accessible/index.md) | `interface WheelchairAccessible` |

### Annotations

| Name | Summary |
|---|---|
| [AlertSeverity](-alert-severity/index.md) | `class AlertSeverity` |
