[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.routing](../index.md) / [TripGroupsSorter](./index.md)

# TripGroupsSorter

`open class TripGroupsSorter`

### Functions

| Name | Summary |
|---|---|
| [checkViolationInvisible](check-violation-invisible.md) | `fun checkViolationInvisible(modeIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, removalModeIdSet: `[`HashSet`](https://docs.oracle.com/javase/7/docs/api/java/util/HashSet.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getMinimizedModeIdsWithoutWalking](get-minimized-mode-ids-without-walking.md) | `fun getMinimizedModeIdsWithoutWalking(minimizedModeIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`HashSet`](https://docs.oracle.com/javase/7/docs/api/java/util/HashSet.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [sort](sort.md) | `open fun sort(sortOrder: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, groups: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TripGroup`](../../skedgo.tripkit.routing/-trip-group/index.md)`>?, willArriveBy: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [updateTripGroupVisibilities](update-trip-group-visibilities.md) | `open fun updateTripGroupVisibilities(tripGroups: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripGroup`](../../skedgo.tripkit.routing/-trip-group/index.md)`>, modePreferences: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TransportModePreference`](../../com.skedgo.tripkit.ui.core.modeprefs/-transport-mode-preference/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
