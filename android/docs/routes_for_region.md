## RegionRoutingRepository

Here, you can retrieve detailed information about routes for either all operators in a region, or a specified operator


## Get routes in a region

With RegionRoutingRepository, you can fetch routes for a specific region by either providing its name or your [`Location`](tripkit-android/com.skedgo.tripkit.common.model/-location/index.md) along with a query, to search for a route name, and operatorId if you have.

Make sure you you've initialized [TripKitUI](https://android.developer.tripgo.com/) to create an instance and access its services

You can access RegionRoutingRepository with `TripKitUI.getInstance().regionRoutingRepository()`

### Get routes with region name, query, modes and operator id

````
 fun getRegionRoutes(
            region: String,
            query: String? = null,
            modes: List<String> = emptyList(),
            operatorId: String? = null
    ): Single<List<RegionRoute>>
````

> #### Parameters
| Name  | Type | Required |
| ------------- | ------------- | ------------- |
| region | String  | Yes |
| query | String | No |
| modes | List<String> | No |
| operatorId | String | No |

> #### Response
(RxJava Single) List of [`RegionRoute`](tripkit-android/com.skedgo.tripkit.regionrouting/com.skedgo.tripkit.regionrouting.data/-regionroute/index.md)

> #### Sample

````kotlin
TripKitUI.getInstance().regionRoutingRepository().getRegionRoutes(
	region = "US_CA_RegionName", 
	query = "Metro",
	modes = listOf("pt_pub_sample"),
	operatorId = "sampleId"

).subscribe {
	// Handle response here
}

````

### Get routes with string query and [`Location`](tripkit-android/com.skedgo.tripkit.common.model/-location/index.md) 

````
 fun getRoutes(
            query: String,
            location: Location?
    ): Observable<List<RegionRoute>>
````

> #### Parameters
| Name  | Type | Required |
| ------------- | ------------- | ------------- |
| query | String | Yes |
| location | [`Location`](tripkit-android/com.skedgo.tripkit.common.model/-location/index.md)  | Yes |

> #### Response
(RxJava Observable) List of [`RegionRoute`](tripkit-android/com.skedgo.tripkit.regionrouting/com.skedgo.tripkit.regionrouting.data/-regionroute/index.md)

> #### Sample

````kotlin
val location: Location? = Location(-33.9504502,151.0309)

TripKitUI.getInstance().regionRoutingRepository().getRoutes(
	query = "Metro",
	location = location
).subscribe {
	// Handle response here
}

````

### Get routes with region name and query

````
 fun getRoutes(
            regionName: String,
            query: String
    ): Single<List<RegionRoute>>
````

> #### Parameters
| Name  | Type | Required |
| ------------- | ------------- | ------------- |
| regionName | String | Yes |
| query | String | Yes |

> #### Response
(RxJava Single) List of [`RegionRoute`](tripkit-android/com.skedgo.tripkit.regionrouting/com.skedgo.tripkit.regionrouting.data/-regionroute/index.md)

> #### Sample

````kotlin
TripKitUI.getInstance().regionRoutingRepository().getRoutes(
	regionName = "US_CA_RegionName"
	query = "Metro"
).subscribe {
	// Handle response here
}

````

## Get details of a route

````
 fun getRegionRouteInfo(
            region: String,
            operatorId: String,
            routeID: Int
    ): Single<RouteDetails>
````

**Parameters**

| Name  | Type | Required |
| ------------- | ------------- | ------------- |
| region | String | Yes |
| operatorId | String | Yes |
| routeID | Int | Yes |


__Response__
(RxJava Single) [`RouteDetails`](tripkit-android/com.skedgo.tripkit.regionrouting/com.skedgo.tripkit.regionrouting.data/-routedetails/index.md)

__Sample__

````kotlin
TripKitUI.getInstance().regionRoutingRepository().getRegionRouteInfo(
	regionName = "US_CA_RegionName"
	operatorId = "Sample_Rail",
	routeID = 123
).subscribe {
	// Handle response here
}

````

## Autocompleter

First, declare RegionRoutingAutoCompleter

````kotlin
private val regionRoutingAutoCompleter: RegionRoutingAutoCompleter = TripKitUI.getInstance().regionRoutingAutoCompleter()
````
or
````kotlin
private val regionRoutingAutoCompleter: RegionRoutingAutoCompleter by lazy {
        TripKitUI.getInstance().regionRoutingAutoCompleter()
    }
````

then setup observer and get result as List<[RegionRoute](tripkit-android/com.skedgo.tripkit.regionrouting/com.skedgo.tripkit.regionrouting.data/-routedetails/index.md)>
````kotlin
regionRoutingAutoCompleter.observe({
            //get results for the queries here as List<RegionRoute>
        }, {
            it.printStackTrace()
        }
````


Use [AutoCompleteQuery](tripkit-android/com.skedgo.tripkit.regionrouting/com.skedgo.tripkit.regionrouting.data/-autocompletequery/index.md) to build a query to send on the RegionRoutingAutoCompleter

>__By Region Name__

````kotlin
AutoCompleteQuery.Builder(
        your_query_here_as_string
).byRegionName(your_region_name_here).build()
````

>__By [Location](tripkit-android/com.skedgo.tripkit.common.model/-location/index.md)__
````kotlin
AutoCompleteQuery.Builder(
                your_query_here_as_string
        ).byLocation(location_object_here).build()
````

Lastly, send the query to the RegionRoutingAutoCompleter
````kotlin
regionRoutingAutoCompleter.sendQuery(
                RegionRoutingAutoCompleter.AutoCompleteQuery.Builder(
                        "sample query"
                ).byRegionName("REGION_NAME").build()
        )
````
and get the result from the observer that you setup earlier.
