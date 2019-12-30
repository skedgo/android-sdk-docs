[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.search](../index.md) / [LocationSearchFragment](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`LocationSearchFragment()`

This is a self-contained location search component which merges search results from both SkedGo's search
results as well as Google Places.

Use it with its Builder:

```
LocationSearchFragment.Builder()
        .withBounds(mMap.projection.visibleRegion.latLngBounds)
        .near(mMap.cameraPosition.target)
        .withHint(getString(R.string.search))
        .allowCurrentLocation(true)
        .allowDropPin()
        .build()
```

