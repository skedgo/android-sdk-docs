[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.core.modeprefs](../index.md) / [IsTransitModeIncludedRepository](./index.md)

# IsTransitModeIncludedRepository

`interface IsTransitModeIncludedRepository`

### Functions

| Name | Summary |
|---|---|
| [getAll](get-all.md) | `abstract fun getAll(): Observable<`[`IsTransitModeIncluded`](../-is-transit-mode-included/index.md)`>` |
| [isTransitModeIncluded](is-transit-mode-included.md) | `abstract fun isTransitModeIncluded(modeId: `[`TransitModeId`](../-transit-mode-id.md)`): Single<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [setIsTransitModeIncluded](set-is-transit-mode-included.md) | `abstract fun setIsTransitModeIncluded(modeId: `[`TransitModeId`](../-transit-mode-id.md)`, isIncluded: `[`IsIncluded`](../-is-included.md)`): Completable` |
