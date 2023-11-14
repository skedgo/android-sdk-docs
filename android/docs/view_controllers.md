

# View Controllers of TripKitUI

[TripKitUI](https://android.developer.tripgo.com/)  provides customizable view controllers for the following high-level features:

-   **Trip planning**  for showing and comparing the different ways of getting from A-to-B, including details screens for each trip both as an overview of the whole trip or the steps of each trip on a mode-by-mode basis.
-   **Public transport departures**  for a specific stop or station with real-time information, including a details screen for each service that shows the route on the map and in a list.
-   **Location search**  including autocompletion for searching by addresses, public transport POIs, or your own data sources.
-   **Customizable home screen**  which ties all of these together, and let's you add additional custom components

Each of these share the following characteristics:

-   Customisation points for colours and fonts
-   VoiceOver accessible
-   Translated into the following languages: Arabic, English, Japanese, 
-   Compatible with Android Phone and Tablet
-   Compatible with Android API 34
-   Compatible with Google Map out of the box, but can also use other map UI layers, such as HERE or OpenStreetMap
-   Source code available

## Real-time departures and service details

![TimetableFragment](https://raw.githubusercontent.com/skedgo/android-sdk-docs/main/android/docs/img/TimetableFragment.png)

The stand-alone view controller  `TKUITimetableControllerFragment` let's you quickly and easily embed public transport departures.

This view controller has the following features:

-   Show departures for an individual stop or larger station
    -   Real-time information where available, including real-time departure and arrival times, service disruptions and crowdedness of individual services.
    -   Optionally with wheelchair accessibility information
    -   Let users set the time of the first departure time
-   Show details of each service
    -   Route on the map
    -   List of stops including arrival and departure time at each stop
    -   Real-time vehicle location where available

It has the following additional customisation point/s:
-   Customizable list of action buttons

## Trip planning and trip details

![TripResultListFragment](https://raw.githubusercontent.com/skedgo/android-sdk-docs/main/android/docs/img/TripResultListFragment.png)

The stand-alone view controller `TKUITripResultsFragment` let's you quickly and easily show routing results between two locations for various modes including combinations of those modes, i.e., this is fully multi-modal and inter-modal.

This view controller has the following features:

-   Show routing results to a specified location from the user's current location, or between specified locations
    -   High-level comparison of trips, showing durations, cost, carbon emissions, and calories burnt
    -   Real-time information, including departure times, traffic, service disruptions, pricing quotes, ETAs
    -   Let users select what modes should be included
    -   Let users set the time to depart or the time to arrive
-   Show details for each trip as an overview

## Trip mode-by-mode overview

![TripResultMapFragment](https://raw.githubusercontent.com/skedgo/android-sdk-docs/main/android/docs/img/TripResultMapFragment.png)

The stand-alone view controller `TKUITripDetailsViewControllerFragment` let's you display details of a trip on a mode-by-mode (or segment-by-segment) basis.

This view controller has the following features:

- Present detailed trip information, including origin, destination, modes of transportation, stops, and schedules.
- Supports various trip sources: individual trips (ViewTrip), groups of trips (TripGroup), and favorite trips (FavoriteTrip).

## Location search

![LocationSearchFragment](https://raw.githubusercontent.com/skedgo/android-sdk-docs/main/android/docs/img/LocationSearchFragment.png)

The  `TKUILocationSearchViewControllerFragment` can be used to provide autocompletion results for addresses, POIs and custom data sources.

It features the following:
- Location Search:
	- You can type in the name of a place, like a restaurant or a city, and the app will help you find it.
- Map Integration:
	- If you want to search for places on a map, this code lets you do that. You can set an area on the map to focus your search.
- Suggestions:
	- It gives you suggestions as you type, like when your phone suggests words when you're texting. These suggestions can be for specific places or types of locations.

## Home screen

The `TKUIHomeViewControllerFragment` can be used as a start-screen for the trip planning, timetable and search components -- while being highly customizable to add arbitrary other features.

The built-in functionality is a search bar at the top, which uses the same search functionality as the dedicated  `TKUILocationSearchViewControllerFragment` but with the search integrated in the home screen UI, along with a directions button to bring up the  [`RouteInputView`](https://android.developer.tripgo.com/search_location).

The purpose of the home screen is then to add individual  _components_, to give users quick access to different section. How to build these, is up to you, but they can be things like:

-   The user's favourites
-   Recently searched locations
-   Nearby locations
-   Access to the user's booked trips
-   Access to the user's tickets

The  [`TripKitUIExample`](https://github.com/skedgo/tripkit-android-ui/tree/master/tripkituisample)  shows to do some of these.