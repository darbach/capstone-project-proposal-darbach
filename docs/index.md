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
  
  * OAuth with Google sign-in.
  * Display an overlay virtual destination marker and route line on the phone camera.
  * Search for destinations.
  * Get location data from OpenStreetMap.
  * Get route data from OpenRouteService.
  * Invite other users to view real-time location and route.

* **Persistent data**

  * History of searches, matching table on the server for portability between devices.
    
* **Device/external services**
  * Location services
  * OpenStreetMap
    * [OpenStreetMap Overpass API](https://wiki.openstreetmap.org/wiki/Overpass_API)
    * [OpenRouteService API](https://openrouteservice.org/dev/#/api-docs)
  
    
## Server component

* **Functionality**
  
  * Share real-time location and route with other users.

* **Persistent data**
  
  * User profile.
  * Save favorite locations with a descriptive name and notes.
  * Save a history of searches.
  * Location-share invitations between users
    
* **External services**

  * [OpenStreetMap Overpass API](https://wiki.openstreetmap.org/wiki/Overpass_API)
  * [OpenRouteService API](https://openrouteservice.org/dev/#/api-docs)
    
## Stretch goals/possible enhancements 

* Display location information for markers (e.g. business hours, phone #, reviews)
* Add personal notes to markers
* Share route progress through standard Google Maps with friends/family who may want to track your location.

