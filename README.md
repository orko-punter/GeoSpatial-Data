# GeoSpatial-Data
To spot main commercial centers in Jaipur. The notebook uses GeoDataFrames for manipullating geospatial data.
3 methods have been used for clustering -> k_means, dbscan, hdbscan.

The spatial data for Jaipur was downloaded from osm(openstreetmap) in the form of geojon file. 
Using the overpy api is the most convenient method. Queries are sent through overpass-turbo to generate 
