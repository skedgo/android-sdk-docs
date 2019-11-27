[tripkit-android](../../index.md) / [com.skedgo](../index.md) / [TripKit](index.md) / [initialize](./initialize.md)

# initialize

`open static fun initialize(@NonNull context: Context, @NonNull tripKit: `[`TripKit`](index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

This gives a chance to provide a custom ``[`TripKit`](index.md). One idea is that we can create ``[`DaggerTripKit`](#) w/ some customized modules.

 Note that you should only use this when you totally understand what you're doing. Otherwise, just go with ``[`#initialize(Configs)`](./initialize.md) instead.

### Parameters

`context` - Context: A ``[`Context`](#) to launch ``[`FetchRegionsService`](../../com.skedgo.tripkit.android/-fetch-regions-service/index.md).

`tripKit` - [TripKit](index.md): Can be created via ``[`DaggerTripKit`](#).`open static fun initialize(configs: `[`Configs`](../../com.skedgo.tripkit/-configs/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)