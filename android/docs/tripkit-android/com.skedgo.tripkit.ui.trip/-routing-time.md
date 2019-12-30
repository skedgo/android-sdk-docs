[tripkit-android](../index.md) / [com.skedgo.tripkit.ui.trip](index.md) / [RoutingTime](./-routing-time.md)

# RoutingTime

`sealed class RoutingTime`

### Extension Functions

| Name | Summary |
|---|---|
| [toTimeTag](to-time-tag.md) | `fun `[`RoutingTime`](./-routing-time.md)`.toTimeTag(): `[`TimeTag`](../com.skedgo.tripkit.common.model/-time-tag/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [ArriveBy](-arrive-by/index.md) | `data class ArriveBy : `[`RoutingTime`](./-routing-time.md) |
| [LeaveAfter](-leave-after/index.md) | `data class LeaveAfter : `[`RoutingTime`](./-routing-time.md) |
| [Now](-now.md) | `object Now : `[`RoutingTime`](./-routing-time.md) |
