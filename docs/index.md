## Summary

Using your device camera, this augmented reality app overlays route data to give you a better sense of direction
and distance to your destination.

## Intended users


* A driver who has an easier time following an augmented reality map.

  > As an Uber driver, I sometimes miss my turns, because I have trouble connecting the turns on my GPS with the cross-streets. Augmented reality makes it simple to understand where I am supposed to turn.

* A geography teacher showing the relative position of locations to students. 

  > My students would have a much better sense of the relative positions of cities, countries, and geographical landmarks, if I could show them the true direction, even through the curvature of the Earth. An augmented reality app would be the perfect to tool to reinforce these ideas.  

## Client component

* **Functionality**

  * Display an overlay virtual destination marker and route line on the phone camera.
  * Search for destinations.
  * Load saved locations from a Google Maps account.
  * Save destinations into a Google Maps account.

* **Persistent data**

  * A history of searched and visited locations.
    
* **Device/external services**

  * Google Maps
    * [Google Maps SDK](https://developers.google.com/maps/documentation/android-sdk/overview)
    * [Google Geocoding API](https://developers.google.com/maps/documentation/geocoding/overview?hl=tr)
  
    
## Server component

* **Functionality**
  
  * Get data from Google Maps and pass it to the client as JSON.

* **Persistent data**

  * Save a history of searched and visited locations.
    
* **External services**

  * [Google Maps API](https://developers.google.com/maps/documentation/android-sdk/overview)
  * [Geocoding API](https://developers.google.com/maps/documentation/geocoding/overview?hl=tr)
    
## Stretch goals/possible enhancements 

* Display location information for markers (e.g. business hours, phone #, reviews)
* Add personal notes to markers
* Share route progress through standard Google Maps with friends/family who may want to track your location.

