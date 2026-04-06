A town on the other side of the Cascades from the coast. The starting point of the campaign.
```leaflet
### Tutorial: https://youtu.be/54EyMzJP5DU
### id must be unique
id: sibah
### Lock pins so they can't be moved
lock: false
### If true, view of map will recenter as you zoom out. 
recenter: true
### If true, disables mouse scroll for zooming in and out of a map. Button controls still work. 
noScrollZoom: false
image: [[Sibah.png]]
### Map Pixel Height x 1 / (Pixels between Bar Scale / 100)
### Map Pixel Width x 1 / (Pixels between Bar Scale / 100) 
### Note that this formula requires adjustments depending on your map. The idea is to determine the number of units between your bar scale. We divide by 100 here because my bar scale measures in 100 units. If your maps scale bar measures in units of 50 them you should divide by 50 instead. The idea is to calculate how many pixels are equal to 1 unit. 
bounds: [[0,0], [9046, 7814]]
height: 600px
width: 100%
### This sets where the map starts by default. Set it to the middle (half) of your bounds. 
lat: 3907
long: 4523
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map. 
minZoom: -4
### Max zoom is 18. 
maxZoom: 2
### Hover mouse over the Reset Zoom icon to see your current zoom level. 
defaultZoom: -8
### How far it zooms in or out with each step. Can be in decimals. 
zoomDelta: 0.5
### This is a string so can be any text. Change it to match your maps measurement scale. 
unit: miles
scale: 1
darkMode: false
```