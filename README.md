# catharinatiledmaps
<img src="https://github.com/catharinadepari/catharinatile/blob/master/tiles/lab4.jpg" width='880'> <br>

# Green Open Spaces in the Center of Seattle<br>
### :newspaper: Introduction
This project is intended to visualize the spatial distribution of **`green open spaces`** in the center of City Seattle.  Major parks that are identified at this leaflet are located in **`Magnolia`** in the West, **`Phinney Ridge`** in the center, **`Windermer`** in the East, and **`Madison Street`** in the South. Street is stressed in the leaflet to emphasize how the streetcar **`I-5 Express`** (red) and **`99`** (brown) might impact not only the accessbility but also the safety of residents and park users.<br>

### :hammer: Tiles, Geographic Area, and Zoom Levels Selection
The layer map was created by using **`Mapbox Studio's Outdoors`** style template [1], which was later modified in terms of colors. Open space was emphasized by increasing the intensity of its green color. Tiles were retrieved from **`QuickMetaTiles`** which cut the layer map into 256 x 256 pixels tiles. There were 12 tilesets reterieved from this process. <br>
**City Seattle** was chosen as the geographic area with coordinates of **`47.662725132346495 latitude`** and **`-122.33827001436774 longitude`** <br>
**Zoom level** of the tile layer was set at**`12`** to provide:
- map's width and heights of  **`1,048,576 pixels `**,
- ground resolution of  **`38.125 meters/pixels`**, and
- map scale (at 96dpi) of **`1: 144, 447.93`**.

## :flags: Acknowledgement
The credit for this project goes to:
- Mapbox Studio for its free map style processes.
- Carto DB for providing the basemap.

### :link: References <br>
[1] Mapbox Studio:  <https://studio.mapbox.com/> <br>
