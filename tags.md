##Useful OSM tag keys

_OSM tags each have a key and a value. The purpose of this list is to help you pick the right keys to use for your exports/processing without having to spend several days looking at http://wiki.osm.org_

### General
* [name](http://wiki.openstreetmap.org/wiki/Name): seems obvious, but don't forget it!
* name:en : English names of places with regular names in other languages
* alt_name, loc_name, official_name, etc.

### Points of interest
* [amenity](http://wiki.openstreetmap.org/wiki/Key:amenity): restaurants, bars, schools, medical facilities
* [leisure](http://wiki.openstreetmap.org/wiki/Key:leisure): parks, gardens, sports facilities
* [sport](http://wiki.openstreetmap.org/wiki/Key:sport): for sports facilities, get the type of sport
* [tourism](http://wiki.openstreetmap.org/wiki/Key:tourism): hotels, tourist information, public art
* [building](http://wiki.openstreetmap.org/wiki/Key:building): various types of buildings
* [shop](http://wiki.openstreetmap.org/wiki/Key:shop): various kinds of shops
* [office](http://wiki.openstreetmap.org/wiki/Key:office): various kinds of offices
* [man_made](http://wiki.openstreetmap.org/wiki/Key:man_made): various other man-made features, like lighthouses, breakwaters, and windmills

### Transportation
* [highway](http://wiki.openstreetmap.org/wiki/Key:highway): streets, footpaths, bike paths, some public transportation
* [service](http://wiki.openstreetmap.org/wiki/Key:service): for highway = service, more information about the type of service road
* [cycleway](http://wiki.openstreetmap.org/wiki/Key:cycleway): bicycle infrastructure, also cycleway:right and cycleway:left
* [railway](http://wiki.openstreetmap.org/wiki/Key:railway): rail facilities
* [public_transport](http://wiki.openstreetmap.org/wiki/Key:public_transport): other public transportation features
* [aeroway](http://wiki.openstreetmap.org/wiki/Key:aeroway): various airport-related things
* [ref](http://wiki.openstreetmap.org/wiki/Key:ref): reference ID for a feature, like an interstate or state highway number
* [route](http://wiki.openstreetmap.org/wiki/Key:route): describes the type of route
* [operator](http://wiki.openstreetmap.org/wiki/Key:operator): who operates the public transportation route, railway, etc.
* Good for road cartography: [bridge](http://wiki.openstreetmap.org/wiki/Key:bridge), [tunnel](http://wiki.openstreetmap.org/wiki/Key:tunnel), [layer](http://wiki.openstreetmap.org/wiki/Key:layer)

### Land cover
* [landuse](http://wiki.openstreetmap.org/wiki/Key:landuse): various human land uses (residential, farms, construction)
* [natural](http://wiki.openstreetmap.org/wiki/Key:natural): includes water, trees, grassland, volcanos, etc.
* [water](http://wiki.openstreetmap.org/wiki/Key:water): for natural = water, get the type of water feature
* [waterway](http://wiki.openstreetmap.org/wiki/Key:waterway): more water features, like rivers

### Boundaries and places
* [boundary](http://wiki.openstreetmap.org/wiki/Key:boundary): various boundaries, including administrative, political, and national parks 
* [admin_level](http://wiki.openstreetmap.org/wiki/Admin_level): for boundary = administrative, how to tell the difference between cities and countries
* [place](http://wiki.openstreetmap.org/wiki/Key:place): cities and neighborhoods, usually represented as points

_Also, check out the osm2pgsql [default style file](https://github.com/openstreetmap/osm2pgsql/blob/master/default.style) for the common keys that it includes_
