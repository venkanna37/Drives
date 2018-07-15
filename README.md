# Map of Bangalore Field Mapping Status

:boom: [Demo](https://venkanna37.github.io/Drives/)

This map is about visualising edits of OpenStreetMap, those were added while field mapping and also showing mapping status of the each area.

As a Goal of Mapping Bangalore, we collected a lot of data with one large team and added to the OpenStreetMap. Data include Road names,Missing streets and Navigation data like

       - Turn Restrictions
       - Stop signs
       - Speed limits
       - Dual carrieageways
       - Traffic signals etc

For collecting and adding data to OpenStreetMap, we used different tools such as 
- [Go Map](https://wiki.openstreetmap.org/wiki/Go_Map!!) for collecting and uploading data to OSM at same time
- [OSM And](https://osmand.net/) for Navigating on field
- [OSM Sketch](https://osm-sketch.soft112.com/) for collecting data
- [JOSM](https://wiki.openstreetmap.org/wiki/JOSM) and [iD Editor](https://wiki.openstreetmap.org/wiki/ID) for adding and editing collected data

## Understanding map

- The map consist of three base layers and one vector interactive layer

         ( ) OpenStreetMap
         ( ) Mapbox Satellite
         (x) Mapbox Drives
         [x] Area Boundaries

 
- In those three base layers OpenStreetMap and Mapbox Satellite are useful for location identification.

- Mapbox drives layer is showing edits of OpenStreetMap those are edited by field mapping, those mapped before going into field using satellite imagery and after coming back from field. The red color roads are edited roads on OpenStreetMap.

<p align = "center" >
<img width = "250" height = "250" src = "/Screenshots/sc3.png">
</p>

- In the above image and map Yellow color indicates mapped areas those are covered in trial drives and Purple color indicates mapped areas those are covered after planning.

- If the cursor is on area of one polygon it shows following details

       - Area name
       - Area in km<sup>2</sup>
       - Team members names

like :point_right: <img align = "center" width = "150" height = "50" src = "/Screenshots/sc2.png">

## Tools used for creating this map
:star: [Leaflet](http://leafletjs.com)

:star: [Mapbox Studio](https://www.mapbox.com/mapbox-studio/)
