# cuba-geojsons
Cuba related geojson files.

Now it has geojson files with cuban provinces and municipalities boundaries.  

For each case there is one file with the region boundaries (municipalieties or provinces) for the whole Cuba and others with the boundaries for each province.

# original sources
To create the geojson files with the municipalities boundaries we used the shapefiles available at the [Spatial Data Repositoy of New York University](https://geo.nyu.edu/catalog/stanford-np147sx1056). The shapefiles were converted to geojson and then corrected, edited and transformed to those that were published.

To create the geojson files with the provinces boundaries we used as base the one published at [Hicuba.com](https://www.hicuba.com/Mapas/geodata/provincias.json). This was corrected, edited and transformed in a similar way as the municipalities geojsons were.

# to be fixed

There are some problems with municipalities boundaries that will corrected in the future. The municipalities with the biggest problems are Esmeralda and Nuevitas, in Camaguey. Esmeralda has a part of its territory (a key) that belongs to Nuevitas. This will be the first thing to be corrected.
