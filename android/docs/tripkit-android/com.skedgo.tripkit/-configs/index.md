[tripkit-android](../../index.md) / [com.skedgo.tripkit](../index.md) / [Configs](./index.md)

# Configs

`@Immutable abstract class Configs`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Configs()` |

### Functions

| Name | Summary |
|---|---|
| [baseUrlAdapterFactory](base-url-adapter-factory.md) | `abstract fun baseUrlAdapterFactory(): `[`Callable`](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Callable.html)`<`[`Callable`](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Callable.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!>?` |
| [builder](builder.md) | `open static fun builder(): Builder!` |
| [co2PreferencesFactory](co2-preferences-factory.md) | `abstract fun co2PreferencesFactory(): `[`Callable`](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Callable.html)`<`[`Co2Preferences`](../-co2-preferences/index.md)`!>?` |
| [context](context.md) | `abstract fun context(): Context!` |
| [debuggable](debuggable.md) | `open fun debuggable(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [errorHandler](error-handler.md) | `abstract fun errorHandler(): Consumer<`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`!>?` |
| [extraQueryMapProvider](extra-query-map-provider.md) | `abstract fun extraQueryMapProvider(): `[`ExtraQueryMapProvider`](../../com.skedgo.tripkit.routing/-extra-query-map-provider/index.md)`?` |
| [isUuidOptedOut](is-uuid-opted-out.md) | `open fun isUuidOptedOut(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [key](key.md) | `abstract fun key(): `[`Callable`](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Callable.html)`<`[`Key`](../../skedgo.tripkit.configuration/-key/index.md)`!>!` |
| [tripPreferencesFactory](trip-preferences-factory.md) | `abstract fun tripPreferencesFactory(): `[`Callable`](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Callable.html)`<`[`TripPreferences`](../-trip-preferences/index.md)`!>?` |
| [userTokenProvider](user-token-provider.md) | `abstract fun userTokenProvider(): `[`Callable`](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Callable.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>?` |
