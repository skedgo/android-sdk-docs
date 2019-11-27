[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresult](../index.md) / [IsLocationPermissionGranted](./index.md)

# IsLocationPermissionGranted

`open class IsLocationPermissionGranted`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `IsLocationPermissionGranted(context: Context)` |

### Properties

| Name | Summary |
|---|---|
| [context](context.md) | `val context: Context` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | Checks if given permission is granted or not. If it's granted, the returned signal will emit true &amp; complete. Otherwise, waits until the permission is granted later. Once it's granted, it will emit true but never complete.`open operator fun invoke(): Observable<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
