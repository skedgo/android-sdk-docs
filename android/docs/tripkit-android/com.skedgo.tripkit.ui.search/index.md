[tripkit-android](../index.md) / [com.skedgo.tripkit.ui.search](./index.md)

## Package com.skedgo.tripkit.ui.search

### Types

| Name | Summary |
|---|---|
| [CurrentLocationSuggestionViewModel](-current-location-suggestion-view-model/index.md) | `class CurrentLocationSuggestionViewModel : `[`SuggestionViewModel`](-suggestion-view-model/index.md) |
| [DropNewPinSuggestionViewModel](-drop-new-pin-suggestion-view-model/index.md) | `class DropNewPinSuggestionViewModel : `[`SuggestionViewModel`](-suggestion-view-model/index.md) |
| [FetchFoursquareLocations](-fetch-foursquare-locations/index.md) | `interface FetchFoursquareLocations : `[`FetchLocations`](-fetch-locations/index.md) |
| [FetchGoogleLocations](-fetch-google-locations/index.md) | `interface FetchGoogleLocations : `[`FetchLocations`](-fetch-locations/index.md) |
| [FetchLocalLocations](-fetch-local-locations/index.md) | `interface FetchLocalLocations : `[`FetchLocations`](-fetch-locations/index.md) |
| [FetchLocations](-fetch-locations/index.md) | `interface FetchLocations` |
| [FetchLocationsParameters](-fetch-locations-parameters/index.md) | `abstract class FetchLocationsParameters` |
| [FetchSuggestions](-fetch-suggestions/index.md) | `interface FetchSuggestions` |
| [FetchTripGoLocations](-fetch-trip-go-locations/index.md) | `interface FetchTripGoLocations : `[`FetchLocations`](-fetch-locations/index.md) |
| [GoogleSuggestionViewModel](-google-suggestion-view-model/index.md) | `class GoogleSuggestionViewModel : `[`SuggestionViewModel`](-suggestion-view-model/index.md) |
| [LocationSearchErrorViewModel](-location-search-error-view-model/index.md) | `class LocationSearchErrorViewModel` |
| [LocationSearchFragment](-location-search-fragment/index.md) | This is a self-contained location search component which merges search results from both SkedGo's search results as well as Google Places.`class LocationSearchFragment : `[`AbstractTripKitFragment`](../com.skedgo.tripkit.ui.core/-abstract-trip-kit-fragment/index.md) |
| [LocationSearchViewModel](-location-search-view-model/index.md) | `class LocationSearchViewModel : `[`RxViewModel`](../com.skedgo.tripkit.ui.core/-rx-view-model/index.md) |
| [SearchErrorType](-search-error-type/index.md) | `sealed class SearchErrorType` |
| [SearchSuggestionChoice](-search-suggestion-choice/index.md) | `sealed class SearchSuggestionChoice` |
| [SuggestionViewModel](-suggestion-view-model/index.md) | `sealed class SuggestionViewModel` |
| [VisibilityState](-visibility-state/index.md) | `enum class VisibilityState` |

### Properties

| Name | Summary |
|---|---|
| [ARG_CAN_OPEN_TIMETABLE](-a-r-g_-c-a-n_-o-p-e-n_-t-i-m-e-t-a-b-l-e.md) | `const val ARG_CAN_OPEN_TIMETABLE: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_INITIAL_QUERY](-a-r-g_-i-n-i-t-i-a-l_-q-u-e-r-y.md) | `const val ARG_INITIAL_QUERY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_NEAR_LAT](-a-r-g_-n-e-a-r_-l-a-t.md) | `const val ARG_NEAR_LAT: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_NEAR_LON](-a-r-g_-n-e-a-r_-l-o-n.md) | `const val ARG_NEAR_LON: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_NORTHEAST_LAT](-a-r-g_-n-o-r-t-h-e-a-s-t_-l-a-t.md) | `const val ARG_NORTHEAST_LAT: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_NORTHEAST_LON](-a-r-g_-n-o-r-t-h-e-a-s-t_-l-o-n.md) | `const val ARG_NORTHEAST_LON: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_QUERY_HINT](-a-r-g_-q-u-e-r-y_-h-i-n-t.md) | `const val ARG_QUERY_HINT: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_SOUTHWEST_LAT](-a-r-g_-s-o-u-t-h-w-e-s-t_-l-a-t.md) | `const val ARG_SOUTHWEST_LAT: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_SOUTHWEST_LON](-a-r-g_-s-o-u-t-h-w-e-s-t_-l-o-n.md) | `const val ARG_SOUTHWEST_LON: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_WITH_CURRENT_LOCATION](-a-r-g_-w-i-t-h_-c-u-r-r-e-n-t_-l-o-c-a-t-i-o-n.md) | `const val ARG_WITH_CURRENT_LOCATION: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_WITH_DROP_PIN](-a-r-g_-w-i-t-h_-d-r-o-p_-p-i-n.md) | `const val ARG_WITH_DROP_PIN: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [KEY_BOUNDS](-k-e-y_-b-o-u-n-d-s.md) | `const val KEY_BOUNDS: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [KEY_CENTER](-k-e-y_-c-e-n-t-e-r.md) | `const val KEY_CENTER: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
