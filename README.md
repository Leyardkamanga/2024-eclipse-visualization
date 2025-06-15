# 2024 Eclipse Visualization

This repository contains a Jupyter Notebook for visualizing the 2024 solar eclipse path over the United States using geospatial data and Python libraries such as GeoPandas and Contextily.

## Project Overview

The notebook demonstrates how to:

- Load and process shapefiles representing eclipse paths (umbra, penumbra, etc.)
- Visualize multiple layers on a map with transparency and styling
- Overlay eclipse data on various basemaps for better geographic context
- Reproject data to a suitable Coordinate Reference System (CRS) for the US region

## Data

The shapefiles used in this project are included in the repository under `eclipse_2024_extracted/`. These shapefiles represent different eclipse path components such as:

- Umbra (total eclipse path)
- Penumbra (partial eclipse contours)
- Duration and obscuration polygons

## Requirements

Make sure you have the following Python packages installed:

- geopandas
- matplotlib
- contextily
- shapely

You can install them via pip:

```bash
pip install geopandas matplotlib contextily shapely
