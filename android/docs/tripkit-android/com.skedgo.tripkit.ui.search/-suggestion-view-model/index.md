[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.search](../index.md) / [SuggestionViewModel](./index.md)

# SuggestionViewModel

`sealed class SuggestionViewModel`

### Properties

| Name | Summary |
|---|---|
| [icon](icon.md) | `val icon: ObservableField<Drawable?>` |
| [onItemClicked](on-item-clicked.md) | `abstract val onItemClicked: `[`TapAction`](../../com.skedgo.tripkit.ui.utils/-tap-action/index.md)`<`[`SuggestionViewModel`](./index.md)`>` |
| [showTimetableIcon](show-timetable-icon.md) | `open val showTimetableIcon: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [subtitle](subtitle.md) | `open val subtitle: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [subtitleTextColor](subtitle-text-color.md) | `val subtitleTextColor: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [subtitleTextColorRes](subtitle-text-color-res.md) | `abstract val subtitleTextColorRes: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [title](title.md) | `abstract val title: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [titleTextColor](title-text-color.md) | `val titleTextColor: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [titleTextColorRes](title-text-color-res.md) | `abstract val titleTextColorRes: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [CurrentLocationSuggestionViewModel](../-current-location-suggestion-view-model/index.md) | `class CurrentLocationSuggestionViewModel : `[`SuggestionViewModel`](./index.md) |
| [DropNewPinSuggestionViewModel](../-drop-new-pin-suggestion-view-model/index.md) | `class DropNewPinSuggestionViewModel : `[`SuggestionViewModel`](./index.md) |
| [GoogleSuggestionViewModel](../-google-suggestion-view-model/index.md) | `class GoogleSuggestionViewModel : `[`SuggestionViewModel`](./index.md) |
