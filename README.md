worldmap
========

Experiments with world choropleth map using Leaflet and GeoJSON.
Based on tutorial from http://leafletjs.com/examples/choropleth.html

Original GeoJSON with world countries from https://github.com/johan/world.geo.json/blob/master/countries.geo.json 
Unfortunately this uses 3-letter ISO country codes so had to be converted to 2-letter using http://en.wikipedia.org/wiki/ISO_3166-1

All aid data from DFID IATI data at http://iatiregistry.org and from Aid Information Platform http://aipbeta.dfid.gov.uk

##Install##
Install folder on any web server. Navigate to /index.html to see the map.

##Files##
###index.html###
Contains main js for initiating the map, referencing the data files

###countries2.js###
GeoJSON file with both properties and co-ordinates for each country.
Properties:
* name
* projects - number of aid projects
* budget - 2013/14 aggregated project budget
* flag - url of flag (not included in this folder yet)


