![Preview of Nite Overlay](preview.jpg "Preview of Nite Overlay")

# Nite Overlay - Overview

Generates an overlay to illustrate the day/night cycle. The night side is shaded slightly darker.

Works with Google Maps API v3

The sun position is estimated using an adapted method from NOAA's solar calculator, which is based on equations from Astronomical Algorithms, by Jean Meeus.  
More details: http://www.esrl.noaa.gov/gmd/grad/solcalc/calcdetails.html

*Might not work on some mobile devices. I've not explored the reason for this*

## Quick start

```javascript
var map = google.maps.Map(...);
nite.init(map);
```
Use to the refresh method to update the position periodically. Perhaps via setInterval();

Note: *If the overlay is hidden and refresh() is called, the overlay position will not be updated.  
Not until the overlay is visible again.*

## Available methods

`nite.setMap()` set a specific map object  
`nite.setDate(Date object)` set a specific datetime, or `null` to use current datetime  
`nite.refresh()` Recalculate and refresh the position of the overlay  
`nite.isVisible()` turns a boolean if the overlay is visible on the map  
`nite.show()` Make the overlay visible  
`nite.hide()` Hide the overlay

