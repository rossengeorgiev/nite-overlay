# Nite Overlay

Generates an overlay to illustrate the day/night cycle on the map. The night side is shaded slightly darker.

## Use

```javascript
var map = google.maps.Map(...);
nite.init(map);
```
Use to the refresh method to update the position periodically. Perhaps via setInterval();

Note: *If the overlay is hidden and refresh() is called, the overlay position will not be updated.  
Not until the overlay is visible again.*

## Methods

`nite.setMap()` set a different map object  
`nite.setDate(Date object)` set a specific datetime, or `null` to use current datetime  
`nite.refresh()` Recalculate and refresh the position of the overlay  
`nite.isVisible()` turns a boolean if the overlay is visible on the map  
`nite.show()` Make the overlay visible  
`nite.hide()` Clear the overlay from the map  

