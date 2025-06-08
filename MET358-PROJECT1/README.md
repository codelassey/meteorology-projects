# Boundary Layer Height Analysis for Navrongo and Tema

## Overview
This repository contains a Jupyter notebook [GROUP6.ipynb](https://github.com/codelassey/meteorology-projects/blob/main/MET358-PROJECT1/GROUP6.ipynb) that analyzes boundary layer height (BLH) data for two locations in Ghana, Navrongo and Tema, on January 1, 2000. The notebook visualizes BLH over a 24-hour period (12 AM to 12 AM) using data from the European Centre for Medium-Range Weather Forecasts (ECMWF). The plot includes markers for diurnal times (12 AM, 6 AM, 12 PM, 6 PM) and typical minimum (6 AM) and maximum (3 PM) temperature times.

## Features
- Data Source: ECMWF dataset with BLH values across a grid (latitude: 4.5°N to 11.5°N, longitude: -3.5°E to 1.5°E) for 24 hourly time steps.
- Visualization: Time-series plot comparing Navrongo (blue line, circular markers) and Tema (red line, square markers) BLH.
- Annotations: Green dashed lines mark diurnal times; blue/red triangles mark min/max temperature times.
- Formatting: Time axis in HH:MM format, with major (3-hour) and minor (1-hour) ticks, and a grid for readability.

## Requirements
To run the notebook, install the following Python packages:
```
pip install xarray matplotlib numpy cartopy
```
If not, you can still view its contents.

Python: 3.12.7

- Libraries:
1. xarray: For handling netCDF data and plotting
2.matplotlib: For creating the time-series plot
3. numpy: For time calculations with timedelta64
4. cartopy: For adding geospatial visualizations:


## Dataset

- Dimensions: valid_time (24 hours), latitude (29 points), longitude (21 points)
- Variable: blh (boundary layer height in meters)
- Time Range: January 1, 2000, 00:00 to 23:00
- Source: ERA5 ECMWF Reanalysis Data [LINK HERE](https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels?tab=download)


