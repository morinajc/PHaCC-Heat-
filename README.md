# Calculating distances between points 

The objective of this script is to calculate distances between points on the WGS ellipsoid using the Raster package. In this example, zipcode/ZCTAs of the state of Virginia were mapped to the nearest Spatial Synoptic Classification (SSC) weather station to assess specific weather patterns. In particuluar, this project is examining weather-type classifications that are associated with extreme heat. The GPS coordinates for SSC stations were obtained from http://sheridan.geog.kent.edu/ssc3.html. Zipcode and ZCTA centroids were obtained from geonames.org and nber.org, respectively. 

Once each centroid has been mapped to the nearest weather station, heat event data for each station will be applied to the appropriate zip/ZCTA, which allows for spatial and temporal patterns of heat event days for the state of Virginia between 2016-2020 to be assessed. This will then be linked to heat-specific illnesses and emergency room admittance. 
