# MET 254 Project 3 : Spatial Plots of Precipitation Flux Data for Ghana

## Project Overview
This repository contains project for MET 254 (Python for Scientific Computing). The objective of the project is to create spatial plots showing the mean precipitation flux (in mm/day) for each month of a past year and a future year (2090) over Ghana, using precipitation flux data from a NetCDF dataset. The plots are overlaid on a map of Ghana, highlighting its ecological zones (Sudan Savannah, Guinea Savannah, Transition Zone, Forest, and Coast).

The project uses Python libraries such as `xarray`, `matplotlib`, `cartopy`, and `PIL` to process the data and generate the visualizations.


## Repository Contents
- `MET254PROJECT3.ipynb`: Jupyter Notebook containing the Python code for data processing and visualization.
- `journal.png`: Map of Ghana showing ecological zones and major cities, used as the base image for the spatial plots.
- `MET254_data.nc`: NetCDF dataset containing precipitation flux data (Note: a download link is provided below).
- `2090_Prep.png`: Output image showing the spatial plots of mean precipitation for each month in 2090.
- `2000_Prep.png`: Output image showing the spatial plots of mean precipitation for each month in 2000.
- `README.md`: This file, providing an overview and instructions for the project.

## Dataset
The dataset `MET254_data.nc` contains precipitation flux data (`rain`) from 1971 to 2100, with dimensions:
- Time: 47,482 time steps (daily data from 1971 to 2100).
- Latitude: 37 points (4.51°N to 12.43°N).
- Longitude: 23 points (-3.41°E to 1.43°E).
- Variable: `rain` (precipitation flux in mm/day).

**Download Link** : [https://drive.google.com/file/d/1xcqejYI0t6XctkujmYDbxd6N8a5eoJb6/view?usp=drive_link].

## Requirements
To run the code in this project, you need the following Python libraries:
- `xarray`
- `matplotlib`
- `cartopy`
- `Pillow` (PIL)
- `numpy` (usually installed with `xarray`)
  
Additionally, you may need to install netCDF4 for reading NetCDF files:
```bash
pip install netCDF4
```

You can install these dependencies using `pip`:
```bash
pip install xarray matplotlib cartopy Pillow numpy
```

```bash
conda install cartopy
```

## Acknowledgments
This project was completed as part of the MET 254 course (Python for Scientific Computing).
Thanks to our instructor, Dr. Edmund Yamba, and teaching assistants Desmond and Patrick for their guidance and support.
