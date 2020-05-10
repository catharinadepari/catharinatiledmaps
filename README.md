# catharinatiledmaps

# Green Open Spaces in the Center of Seattle<br>
### :newspaper: Introduction
This project is intended to visualize the spatial distribution of **`green open spaces`** in the center of City Seattle **[1]**. Two major parks indicated at the maximum zoom of the tile map, which are **`Discovery Park Ballard`** in the West and **`Wodland Park Roosesevelt`** near the Green Lake. Woodland Park is situated in the residential complex comprising of single and multi family houses. It is relatively accessible from any corner of the city center's neighborhoods, different from the Discovery Park which is relativey isolated. Street is highlighted here by changing its color into an intense red to emphasize the impacts of the streetcar I-5 Express and 99 on the accessbility and safety of residents and park users.The tile is retrieved from Mapbox Studio's Outdoors style template which uses open space as one of its layers. <br>

### :hammer: Tiles, Geographic Area, and Zoom Levels Selection
<img src="C:\images\lab4.jpg" width='950'> <br>

The tiles used to emphasize the green open space in the central part of Seattle is retrieved from Mapbox Studio <https://studio.mapbox.com/> and rendered by QuickMetaTiles which cut the tiles into 256 x 256 pixels tiles. There are 12 tilesets reterieved from this process. <br>
**City Seattle** is chosen as the geographic area with coordinates of **`47.662725132346495 latitude`** and **`-122.33827001436774 longitude`**. <br>
**Zoom level** of the tile layer is **`12`** which indicates:
- map's width and heights of about **`1,048,576 pixels `**,
- ground resolution of about **`38.125 meters/pixels`**, and
- map scale (at 96dpi) of about **`1: 144, 447.93`**.

## :flags: Acknowledgement
The credit for this project goes to:
- Mapbox Studio for its free map style processes.
- Carto DB for providing the basemap.

### :link: References <br>
[1] Mapbox Studio:  <https://studio.mapbox.com/> <br>
