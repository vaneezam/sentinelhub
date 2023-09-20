# Introduction
Sentinel Hub is a comprehensive platform for accessing and analyzing satellite imagery, particularly from the European Space Agency's Sentinel series. This platform offers a user-friendly interface and a versatile API for seamless retrieval of a diverse range of Earth observation data. <br>
Official documentation of Sentinel Hub can be found here: [Sentinel Hub Documentation](https://docs.sentinel-hub.com/api/latest/)

# Content
The notebook contains code for acquiring time-series satellite data for custom datasets. <br>
Supported functionalities include: <br>
* Evalscript
  * 12 band Sentinel 2 data
  * 3 band RGB 
  * 1 band NDVI
  * 1 band DataMask
* Data
  * acquire data for bounding boxes
    * bounding box to dimension
    * bounding box to resolution
  * acquire data for arbitrary polygons
    * parsing single polygon data 
    * parsing multipolygon data
* Preprocessing
  * renaming files with acquired timestamp
  * seperate the acquired tiff and json files
  * Remove cloudy or erroneous files
  
Current Sentinel hub version: 3.6.1.
