# Nite Overlay

Generates an overlay to illustrate the day/night cycle on the map. The night side is shaded slightly darker.

## Use

```javascript
var map = google.maps.Map(...);
nite.init(map);
```

Use to the refresh method to update the position periodically. Perhaps via setInterval();

## Methods

`nite.setMap()` set a different map object
`nite.refresh()` Recalculate and refresh the position of the overlay  
`nite.show()` Make the overlay visible  
`nite.hide()` Clear the overlay from the map

