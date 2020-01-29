> **Note**: this page is only a draft, but this project is hosted on a [public repository](https://github.com/hhkaos/awesome-arcgis) where anyone can contribute. Learn how to [contribute in less than a minute](https://github.com/hhkaos/awesome-arcgis/blob/master/CONTRIBUTING.md#contributions).

# Raster data types

Rasters are digital aerial photographs, imagery from satellites, digital pictures, or even scanned maps.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of contents**

  - [Introduction](#introduction)
  - [Raster data types](#raster-data-types)
  - [Training](#training)
  - [Videos](#videos)
- [Additional resources](#additional-resources)
  - [Localized resources](#localized-resources)
    - [Spanish](#spanish)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Introduction

The raster model represents the surface of the earth as a grid of cells of equal size (square meter, square mile, ...) is usually used to represent continuous phenomena such us precipitation, elevation, heat from a forest fire, etc..

Each grid contains a discrete or continuous value. Examples:

* Discrete can have values that represent a code for a particular category. For example could be values defining the land type / land cover (1=backgound, 2=oak-pine, etc.)
* Continuous an elevation raster where each value define the altitude of that point

![Raster data](http://desktop.arcgis.com/en/arcmap/latest/manage-data/raster-and-images/GUID-6754AF39-CDE9-4F9D-8C3A-D59D93059BDD-web.png)

> Learn more: [What is raster data?](http://desktop.arcgis.com/en/arcmap/latest/manage-data/raster-and-images/what-is-raster-data.htm)

Raster data types could be classified in many different ways,

* **Number of spectral bands**: sunlight consist of more wavelengths of electromagnetic radiation than the human eye can see (images are single band or multispectral)
    * **Single bands**: grayscale imagery, DEM (Digital Elevation Model), 3D imagery (DTM and DSM)
    * **Multispectral**: NaturalColor, color infrared, NDMI, NDVI, ...

* **Imagery sources** (Sensor platforms):
    * Satellites: Landsat, MODIS, Sentinel, WorldView, ...
    * Aerial: aircrafts, helicopters, balloons, drones (UAVs), blimps and dirigibles, rockets, pigeons, kites, parachutes, ...
    * Ground based: vehicle-mounted poles, stand-alone telescoping, handheld, ...

* **Sensor type used**:
    * Passive (record reflected sunlight): cameras, spectrometers
    * Active (emit energy and record reflected radiation): Lidar, Radar, Sonar

* **Number of dimensions**: unidimensional or multidimensional.

* **Use type**: basemap, multispectral, temporal, event, elevation, ...

## Raster data types

> PENDING TO REVIEW THIS CLASSIFICATION

There are two main raster data types:

* [Aerial photography, aerial imagery or airborne imagery](./aerial-imagery/README.md): photographs from an flying object (aircraft, helicopters, UAVs (or "drones"), etc.
* [Satellite imagery (from satellite sensors)](./satellite-sensor/README.md)
* [Multidimensional data](./multidimensional/README.md): refers to data normally stored as variables, where each variable is a multidimensional array.

Digital pictures, or even scanned maps.

## Training

* [ArcGIS Imagery Book](https://learn.arcgis.com/en/arcgis-imagery-book)
* [ArcGIS Imagery Book - Instructional Guide](http://downloads.esri.com/LearnArcGIS/pdf/instructional-guide-for-the-arcgis-imagery-book.pdf)

## Videos

[Imagery Youtube Playlist](https://www.youtube.com/playlist?list=PLahIW2YFPQd5uO1xe6QmO2wsQHfWnRs-B)

* [Imagery Sources and Usage in ArcGIS](https://www.youtube.com/watch?v=pnoj24ncZas&t=5s)
* [Python: Working with Raster Data](https://www.youtube.com/watch?v=1jx5uRwLld8&t=2625s)

# Additional resources

## Localized resources

### Spanish

* [Imágenes y Teledetección: Conceptos básicos del tratamiento de imágenes en la Plataforma ArcGIS](https://geogeeks.maps.arcgis.com/apps/Cascade/index.html?appid=5072b8d56cef4f7bb5d24e5d840461da)
* [Tratamiento de imágenes Sentinel-2 con ArcGIS](https://storymaps.arcgis.com/stories/8cf7c8024f6e4eb1bbb1d977bda137cf)
