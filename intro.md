![logo](https://climate.copernicus.eu/sites/default/files/2025-03/logoline_c3s.png)

# C3S Climate Indicators Tutorial

**PLEASE NOTE THAT THIS A DEVELOPMENT INSTANCE, THESE NOTE BOOKS ARE OFFICIALLY PUBLISHED ELSEWHERE**

This Jupyter book is a sub-module of the core C3S training material, it is published here for reviewing the
content prior to publication.

## Introduction to Climate Indicators

Climate indicators are key metrics used to quantify various aspects of the climate system, providing insights into trends, patterns, and anomalies. This tutorial offers an introduction to climate indices, covering their definition, calculation methods, and interpretation.

### Windchill Index Calculation

This tutorial will demonstrate how to combine multiple variables of climate data to create an index. The example provided is of the wind speed index, but similar principles can be applied to many other types of single or multi-variable indices.

The data is provided by Copernicus Climate Change Service (C3S) and includes regional climate reanalysis data (UERRA) of wind speed and temperature over Europe from 1961 to 2019.

The tutorial will first show how to download the necessary data from the C3S Climate Data Store (CDS). It will then describe how to apply a commonly used Wind Chill Index formula to the data, and finally plot a map of the wind chill climatology for a particular day over Europe.

The steps shown in this tutorial can be applied to other climate datasets, such as the 5th version of the ECMWF Reanalysis (ERA5), or other data.

![logo](./img/climate_indices.png)

### Working with the GTSMip dataset of global tides and surges

This notebook provides a practical introduction on how to access, visualize and analyse [GTSMip tide and surge water level timeseries](https://cds.climate.copernicus.eu/datasets/sis-water-level-change-timeseries-cmip6?tab=overview) data available in the Climate Data Store (CDS) of the Copernicus Climate Change Service (C3S), developed by Deltares in order to accompany the dataset. This data is the output of the the global tide and surge model [GTSMv3.0](https://www.deltares.nl/en/expertise/projects/global-modelling-of-tides-and-storm-surges).

### End-to-end agroclimatic indicator generation

This notebook demonstrates the process of computing a \"Warm and wet days\" (WW) indicator (https://confluence.ecmwf.int/pages/viewpage.action?pageId=278550975), based on a climate projection.
