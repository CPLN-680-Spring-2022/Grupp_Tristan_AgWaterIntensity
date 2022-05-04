# Grupp_Tristan_AgWaterIntensity

This repository contains the scripts, descriptions, reports and some of the raw data for a project on groundwater extraction and agricultural intensity in Ica, Peru.

1. scripts
- Landsat 8 Image Acquisiton Script GEE.txt is a GEE script used to mask the two week Landsat-8 image collections, calculate NDVI on those collections, and mosaic them with max() for export and use in Ica Ag Water Intensity.Rmd
- Sentinel 2 Image Acquisiton Script GEE.txt is a GEE script used to mask the two week Sentinel-2 image collections, calculate NDVI on those collections, and mosaic them with max() for export and use in Ica Ag Water Intensity.Rmd
- Planet Basemap GEE Export.txt is a GEE for pulling Planet data for potential data fill-in. This was not used in the data fill-in.
- Precipitation CHRIPS GEE Export.txt is a GEE script that pulls CHIRPS data that was related to each of the HydroSHED basins in the Ica Valley.
- Ica Ag Water Intensity.Rmd relates the Sentinel-2 and Landsat 8 image mosaics to the segmented field polygons, calculates the NDVI persistence, and contains some of the code for breakpoint detection.

2. Raw Data
- This folder contains "Planet x NICFI Basemap Ica Dates - Sheet1.csv". This file shows the dates of Planet images that are available through Google Earth Engine (GEE). The dates can be used to filter the image collection.
- The "Ica Rain Tables" folder contains the output of CHIRPS Precipitation process related to the two HydroSHEDS within the Ica Valley. 
