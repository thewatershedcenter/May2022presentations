# State of Lidar for Natural Resources

### Tim Bailey 
### Watershed Research and Training Center


## Airborne Laser scanning and photogrammetry
Both Lidar and Photogrammetry make point clouds
+ ALS Airborne Lidar Surverys 
+ TLS 
+ MLS 
+ UAVs

Traditional Photogrammetry

History of public landscape scale tasked remote sensing in CA
+ Early Air photos
+ Soil Conservation Service and USACE 1939 -1945
+ SCS standardization and technical development of photogrammetryTimber Tax era, high quality photogrammetric stand inventories
+ NHP to NAIP transition   

ALS acquisition history         ppm, int, tech development
+ B4, NSF, NOAA
+ ARRA
+ First Gen 3dep
+ Current public lidar in California
+ Geospatial investment going forward

contrast with traditional geospatial objects 
+ rasters, 
+ simple feature vectors
+ vs Point clouds
+   decimation example 

A look at a LAS file structure             
+ XYZICRGB and the 
+ other lidar specific variables

LAZ compression
+ File Sizes, Memory Management, various kinds of performance constraints tradeoffs
+ LAZ 1.4 type 6,7,8 spec

EPT/COPC 
+ The current state of the USGS Entwine service 
+ Cloud Optimized Point Clouds 
+ Range read features 

Accessing Public Cloud Lidar assets
+ Rockyweb
+     https://geozoneblog.wordpress.com/2021/11/17/good-ol-rockyweb/   A good overview of tools for accessing Rockyweb
+     https://rockyweb.usgs.gov/
+ USGS entwine service
+     https://usgs.entwine.io/
+ Noaa lidar
+     https://coast.noaa.gov/dataviewer/#/lidar/search/
+ Opentopo
+     https://opentopography.org/

Point Cloud operations 
+ filter 
+ select
+ object segmentation
+ relations
+ cloud to cloud comparison, determination of change vs digital elevation model of difference approaches
+ Classification

Detail view of 
+ high level classfication, 
+ filtering, 
+ selection, 
+ object segmentation, and 
+ relationships

Raster extraction
+ Subpixel interpolation
+ Logical conditions
+ Statistical characterization within pixels

Derived raster product
+ Specification 
+ Resolution 
+ Determining suitability of applications 
