[tripkit-android](../index.md) / [com.skedgo.tripkit.ui.trip](./index.md)

## Package com.skedgo.tripkit.ui.trip

### Types

| Name | Summary |
|---|---|
| [ArriveBy](-arrive-by/index.md) | `data class ArriveBy : `[`RoutingTime`](-routing-time.md) |
| [LeaveAfter](-leave-after/index.md) | `data class LeaveAfter : `[`RoutingTime`](-routing-time.md) |
| [Now](-now.md) | `object Now : `[`RoutingTime`](-routing-time.md) |
| [RoutingTime](-routing-time.md) | `sealed class RoutingTime` |

### Functions

| Name | Summary |
|---|---|
| [toRoutingTime](to-routing-time.md) | `fun `[`TimeTag`](../com.skedgo.android.common.model/-time-tag/index.md)`.toRoutingTime(tz: DateTimeZone): `[`RoutingTime`](-routing-time.md) |
| [toTimeTag](to-time-tag.md) | `fun `[`RoutingTime`](-routing-time.md)`.toTimeTag(): `[`TimeTag`](../com.skedgo.android.common.model/-time-tag/index.md) |
