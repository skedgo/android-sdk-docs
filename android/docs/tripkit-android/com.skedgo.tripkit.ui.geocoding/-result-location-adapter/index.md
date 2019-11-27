[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.geocoding](../index.md) / [ResultLocationAdapter](./index.md)

# ResultLocationAdapter

`interface ResultLocationAdapter<T : Place!>`

### Functions

| Name | Summary |
|---|---|
| [getPlace](get-place.md) | `abstract fun getPlace(): T` |

### Inheritors

| Name | Summary |
|---|---|
| [AppResultLocationAdapter](../-app-result-location-adapter/index.md) | `class AppResultLocationAdapter : `[`ResultLocationAdapter`](./index.md)`<TripGoPOI!>, `[`GCAppResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-app-result-interface/index.md) |
| [FoursquareResultLocationAdapter](../-foursquare-result-location-adapter/index.md) | `class FoursquareResultLocationAdapter : `[`GCFoursquareResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-foursquare-result-interface/index.md)`, `[`ResultLocationAdapter`](./index.md)`<TripGoPOI!>` |
| [GoogleResultLocationAdapter](../-google-result-location-adapter/index.md) | `class GoogleResultLocationAdapter : `[`GCGoogleResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-google-result-interface/index.md)`, `[`ResultLocationAdapter`](./index.md)`<WithoutLocation!>` |
| [SkedgoResultLocationAdapter](../-skedgo-result-location-adapter/index.md) | `class SkedgoResultLocationAdapter : `[`GCSkedGoResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-sked-go-result-interface/index.md)`, `[`ResultLocationAdapter`](./index.md)`<TripGoPOI!>` |
