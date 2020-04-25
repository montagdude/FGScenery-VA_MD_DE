# FGScenery-VA_MD_DE

Custom FlightGear scenery for Virginia, Maryland, Delaware, and DC.
Data sources:
* Landcover: National landcover database (NLCD):
  https://www.usgs.gov/centers/eros/science/national-land-cover-database
* Elevation: Shuttle Radar Topology Mission 3-arc-second (SRTM-3), void-filled version:
  https://earthexplorer.usgs.gov/
* Rivers and waterbodies: National Hydrography Dataset (NHD):
  https://www.usgs.gov/core-science-systems/ngp/national-hydrography
* Buildings, roads, pylons, other objects: OpenStreetMap using osm2city:
  https://www.openstreetmap.org/
  https://osm2city.readthedocs.io/en/latest/
* Custom materials: National Agriculture Imagery Program (NAIP):
  https://earthexplorer.usgs.gov/

The git repository includes the scripts used to generate the scenery, but it does not include all the input data. To just download the scenery itself, go to the Releases page and download the zip archives.

Installation and Usage
================================================================================
To install, download VA_MD_DE.zip from the Releases page and extract the files wherever you like. Point FlightGear to the directory with the --fg-scenery command line option, the FG_SCENERY environment variable, or add it to Additional Scenery Folders in the GUI. To use the custom materials, download FGData.zip, extract, and copy the contents to the appropriate locations in your FGData directory (aka $FG_ROOT). For example, eastern-us.xml and materials.xml go in $FG_ROOT/Materials/regions, and the textures go in $FG_ROOT/Textures/Terrain.

For the best experience, if your computer can handle it, turn on OSM buildings and detailed roads and pylons under Rendering Options.

Screenshots
================================================================================

![alt tag](https://raw.githubusercontent.com/montagdude/FGScenery-VA_MD_DE/master/screenshots/laurel_bed_lake.png)
Laurel Bed Lake, VA

![alt tag](https://raw.githubusercontent.com/montagdude/FGScenery-VA_MD_DE/master/screenshots/ocean_city.png)
Ocean City, MD

![alt tag](https://raw.githubusercontent.com/montagdude/FGScenery-VA_MD_DE/master/screenshots/richmond1.png)
Richmond, VA

![alt tag](https://raw.githubusercontent.com/montagdude/FGScenery-VA_MD_DE/master/screenshots/richmond2.png)
Richmond, VA

![alt tag](https://raw.githubusercontent.com/montagdude/FGScenery-VA_MD_DE/master/screenshots/washington_dc.png)
Washington, DC with KDCA in the distance
