## webapp_phase3

# STUDENT LOST IN NY (SLNY)

## KEYWORDS

* Districts center 
* District as an Object

## DATASETS
### NY Districts geoshapes
#### LINK
https://services5.arcgis.com/GfwWNkhOj9bNBqoJ/arcgis/rest/services/nycd/FeatureServer/0/query?where=1=1&outFields=*&outSR=4326&f=geojson
#### DATA TYPE
geoJSON
#### UTILITY
Used to know the shape of each district and then comparate with "Neighborhood Names GIS" to know if is habitable 
### Neighborhood Names GIS
#### LINK
https://data.cityofnewyork.us/api/views/xyye-rtrs/rTows.json?accessType=DOWNLOAD
#### DATA TYPE
JSON
#### UTILITY
Used to know the location of the neighborhoods can determinate what districts are habitable.

## Delivery Description

In this delivery the user can not visualize anything, the business logic of the App has all the progress. Now is possible know the approximate center of every district which will be use in the future to know the distance to the university. Moreover, every district was separated since the GeoJSON, this will be helpful to know if a point of a dataset is contained in the district polygon. On the other hand, the app can extract data's crimes and know in which district was committed. Also, all the boroughs in the map has different color guided by color theory.
## Used Browsers

* Google Chrome
## 
