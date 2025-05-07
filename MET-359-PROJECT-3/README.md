# Atmospheric Science Field Work - Precipitation Analysis Over Ghana (2000-2009)

## Project Overview
This project is part of MET359 (Atmospheric Science Field Work) and focuses on analyzing precipitation trends over Ghana from 2000 to 2009 using climate data. The analysis includes identifying extreme precipitation events and visualizing spatial distributions using Python.



## Dataset
- **Source**: The dataset used is `Africa_cru_data.nc`. You can download it [HERE](https://drive.google.com/file/d/1oJI2GUL3S4aPEzmtlaQb4tJ1LHhH9rM3/view?usp=share_link)
- **Variable of Interest**: Precipitation (`pre`)
- **Time Range**: 2000-2009
- **Geographical Scope**: Ghana (Latitude: 4.5°N to 11.5°N, Longitude: -3.5°E to 1.5°E)

## Methodology
1. **Data Loading**:
   - The NetCDF file is loaded using `xarray`.
2. **Data Slicing**:
   - The precipitation variable is extracted and spatially filtered to cover Ghana.
3. **Extreme Precipitation Events**:
   - Events exceeding 250 mm of precipitation are identified and counted per year.
4. **Visualization**:
   - Annual maps of extreme precipitation events are generated using `matplotlib` and `cartopy`.

## Requirements
To run this project, install the required dependencies:
```bash
pip install xarray matplotlib cartopy numpy
