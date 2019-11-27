[tripkit-android](../index.md) / [com.skedgo.geocoding.agregator](./index.md)

## Package com.skedgo.geocoding.agregator

### Types

| Name | Summary |
|---|---|
| [GCAppResultInterface](-g-c-app-result-interface/index.md) | Information that the user saves in the app`interface GCAppResultInterface : `[`GCResultInterface`](-g-c-result-interface/index.md) |
| [GCBoundingBoxInterface](-g-c-bounding-box-interface/index.md) | `interface GCBoundingBoxInterface` |
| [GCFoursquareResultInterface](-g-c-foursquare-result-interface/index.md) | `interface GCFoursquareResultInterface : `[`GCResultInterface`](-g-c-result-interface/index.md) |
| [GCGoogleResultInterface](-g-c-google-result-interface/index.md) | `interface GCGoogleResultInterface : `[`GCResultInterface`](-g-c-result-interface/index.md) |
| [GCQueryInterface](-g-c-query-interface/index.md) | `interface GCQueryInterface` |
| [GCResultInterface](-g-c-result-interface/index.md) | `interface GCResultInterface` |
| [GCSkedGoResultInterface](-g-c-sked-go-result-interface/index.md) | `interface GCSkedGoResultInterface : `[`GCResultInterface`](-g-c-result-interface/index.md) |
| [MGAResultInterface](-m-g-a-result-interface/index.md) | this class represents a scored result, it could be single or have duplicates`interface MGAResultInterface<T : `[`GCResultInterface`](-g-c-result-interface/index.md)`!> : `[`Serializable`](https://docs.oracle.com/javase/7/docs/api/java/io/Serializable.html) |
| [MultiSourceGeocodingAggregator](-multi-source-geocoding-aggregator/index.md) | Scoring formulas Favourites: max(title, address) Search history: max(title, address) Regions: distance Address book: (title + address) / 2 Calendar: (title + address) / 2 SkedGo transit stops: popularity -&gt; ((min(popularity, GOOD_SCORE)) / (GOOD_SCORE / 100)) * 2 SkedGo others: title Google: (max(title, address) * 3 + distance) / 4 Google Autocomplete: (title * 3) / 4 Foursquare: ((title * 3 + distance) / 4) * suburb Title score: score based on input string against the title of the result Address score: score based on input string against address of the result Distance score: score based on distance to center or provided region Suburb score: bonus score if result is a suburb Popularity score: score based on popularity of result as determined by server`open class MultiSourceGeocodingAggregator<T : `[`GCResultInterface`](-g-c-result-interface/index.md)`!>` |
