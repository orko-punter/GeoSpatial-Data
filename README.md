# To spot main commercial centers in Jaipur

The notebook uses GeoDataFrames for manipullating geospatial data.     
3 methods have been used for clustering -> k_means, dbscan, hdbscan.


# Data-Extraction
The geospatial data for Jaipur was downloaded from osm(openstreetmap) in the form of geojon file. 
Using the overpy api is the most convenient method. Queries in the proper format are sent                                 through overpass-turbo to generate requests followed by exporting the geoson files.
Generating queries in the proper format was done through fstring in python.
