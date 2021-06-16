# Map of Bangalore Field Mapping Status

:boom: [Demo](https://venkanna37.github.io/Drives/)

Drives repository created to visualise edits in OpenStreetMap those added during field mapping. Along with visualising edits, this map shows the mapping status of each AOI (that prepared while planning field trips). Planning and organising field mapping events is part of one of the project. We, with the team from Mapbox, collected massive data in Bangalore and added it to OpenStreetMap. The collected data include road/street names, missing streets and navigation information such as...

       - Turn Restrictions
       - Stop signs
       - Speed limits
       - Dual carrieageways
       - Traffic signals etc

To collect and add data to OpenStreetMap, we used various tools such as 
- [GoMap](https://wiki.openstreetmap.org/wiki/Go_Map!!) to collect and uplode data from field to OpenStreetMap
- [OSMAnd](https://osmand.net/) to navigate in through planned route 
- [OSM sketch](https://osm-sketch.soft112.com/) to note down the data on map digitally
- [JOSM](https://wiki.openstreetmap.org/wiki/JOSM) and [iD Editor](https://wiki.openstreetmap.org/wiki/ID) to add and edit the data in OSM after coming back from field

## Understanding map

- The map consist of three base layers and one vector interactive layer

         ( ) OpenStreetMap
         ( ) Mapbox Satellite
         (x) Mapbox Drives
         [x] Area Boundaries

 
- In those three base layers OpenStreetMap and Mapbox Satellite are useful for location identification.

- Mapbox Drives layer created in Mapbox Studio shows changesets ( list of modifications)  in OpenStreetMap. These modifications consist of changesets before going into the field using satellite imagery and changesets from the field—all changesets represented with red colour on the map.

<p align = "center" >
<img width = "250" height = "250" src = "/Screenshots/sc3.png">
</p>

- In the above image, yellow color represents mapped areas those are covered in trial field trips and purple color represents mapped areas those are covered after planned field trips.

- If cursor hover over polygons, map shows following details

       - Area name
       - Area in Square kilo meters
       - Team members names

like :point_right: <img align = "center" width = "150" height = "50" src = "/Screenshots/sc2.png">

## Tools used for creating this map
:star: [Leaflet](http://leafletjs.com)

:star: [Mapbox Studio](https://www.mapbox.com/mapbox-studio/)
