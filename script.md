# GDAL 101 Workshop Instructor's Script

## Introduction

Good [morning/afternoon]! Today, I’ll introduce you to GDAL, a cornerstone of geospatial data handling.

**What is GDAL?**  
GDAL, or the Geospatial Data Abstraction Library, is an open-source library for reading, writing, and manipulating geospatial data. Originally developed in 1998 by Frank Warmerdam, GDAL was a breakthrough because it offered a unified way to work with a huge range of spatial data formats. With GDAL, users can easily process both raster and vector data, making it a true Swiss Army knife for geospatial applications.

**A Brief History**  
GDAL emerged when the geospatial field was fragmented by numerous data formats—each with its own quirks and complexities. Warmerdam, recognizing the need for a standardized way to manage these formats, developed GDAL as an open-source project. It gained traction quickly and has grown continuously, maintained by an active community under the Open Source Geospatial Foundation, or OSGeo.

**Ubiquity and Reach**  
Today, GDAL is everywhere. Major GIS platforms, from QGIS and ArcGIS to cloud-based solutions like Google Earth Engine, either use or support GDAL. It’s a staple in data science, remote sensing, agriculture, and urban planning, and it powers countless workflows across industries. Because GDAL is open-source and compatible across operating systems, it’s become a universal language for handling geospatial data, bridging academia, government, and industry.

**Why is GDAL So Useful?**  
GDAL’s strength lies in its versatility. It supports over 200 raster and 100 vector formats, allowing users to convert, reproject, and analyze data seamlessly. Whether you need to convert satellite imagery into a different format, reproject data to another coordinate system, or extract and manipulate vector features, GDAL has tools for it all. It’s scriptable, fast, and works well with languages like Python, making it ideal for automation and large-scale data processing.

GDAL’s open-source foundation, robust format support, and active development have made it indispensable in the geospatial world. For anyone working with spatial data, mastering GDAL unlocks a powerful set of tools that make data processing more efficient and accessible. Thank you!

### Welcome and Overview
- Welcome participants to the GDAL 101 Workshop.
- Provide a brief overview of GDAL and its importance in geospatial data processing.
- Explain the structure of the workshop and what participants will learn.

## Section 1: Installation

### Installing Necessary Packages
- Discuss the importance of installing GDAL and leafmap.
- Explain the command to install these packages using `pip`.

## Section 2: Verification

### Verifying GDAL Installation
- Explain the importance of verifying the GDAL installation.
- Discuss the code block that imports GDAL and prints its version.

## Section 3: Download the Data

### Placeholder for Data Download
- Mention that this section is a placeholder for downloading the necessary datasets.
- Explain where participants can find the datasets and how to download them.

## Section 4: Check out the Data in QGIS

### Placeholder for QGIS
- Discuss the importance of visualizing data in QGIS.
- Explain that this section is a placeholder for instructions on how to open and inspect the data in QGIS.

## Section 5: OGR for Vector Data

### Inspecting Vector Data
- Explain the use of `ogrinfo` to inspect vector data.
- Discuss the commands provided to inspect shapefiles and their attributes.

## Section 6: GDAL for Raster Data

### Inspecting Raster Data
- Explain the use of `gdalinfo` to inspect raster data.
- Discuss the commands provided to inspect raster files and their metadata.

## Section 7: Converting Data

### Exporting Original Data into New Formats
- Discuss the importance of data conversion in GIS.
- Explain the commands to list available formats and convert shapefiles to GeoJSON and GeoTIFF to PNG.

## Section 8: Reprojecting Data

### Reprojecting Vector and Raster Data
- Explain the concept of coordinate reference systems (CRS) and the need for reprojection.
- Discuss the commands to reproject shapefiles and raster files to a different CRS.

## Section 9: Querying Data

### Querying Data Using SQL with GDAL
- Explain the use of SQL queries to extract specific data from vector files.
- Discuss the commands to count features, select specific features, and save query results to new files.

## Section 10: Clipping to Create New Data

### Clipping Data Using GDAL
- Explain the concept of clipping data to create new datasets.
- Discuss the commands to clip vector and raster data using a GeoJSON file.

## Section 11: Previewing Data

### Using Folium to Preview Data
- Explain the use of Folium for interactive map visualization.
- Discuss the code block that loads a GeoJSON file and creates an interactive map centered around the data.

## Conclusion

### Recap and Q&A
- Recap the key points covered in the workshop.
- Open the floor for any questions from the participants.
- Provide additional resources for further learning.
