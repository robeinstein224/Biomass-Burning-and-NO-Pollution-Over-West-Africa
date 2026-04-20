# Biomass Burning and NO₂ Pollution Over West Africa

## Overview

This project analyzes the relationship between biomass burning and nitrogen dioxide (NO₂) pollution across West Africa. Biomass burning, driven by agricultural activities and seasonal fires, is a major source of atmospheric pollution in the region. Using satellite-derived datasets, this study explores how fire activity influences air quality over time and space.

## Objectives

* Examine spatial distribution of NO₂ concentrations
* Analyze seasonal variability (DJF, MAM, JJA, SON)
* Investigate the link between Fire Radiative Power (FRP) and NO₂ levels
* Identify pollution hotspots across the region

## Data and Tools

The analysis uses satellite-based NO₂ and FRP datasets, along with geographic boundary data for West Africa. Key tools and libraries include Python, NumPy, Pandas, Xarray, Matplotlib, and Cartopy for geospatial visualization.

## Methodology

Data were preprocessed and filtered to the West African region. Monthly averages were computed and further aggregated into seasonal means. Spatial analysis was performed using geographic masks, and results were visualized using multi-panel maps with consistent color scales. Classification techniques such as quantile-based binning were applied to improve interpretability.

## Results

The results show clear seasonal patterns in NO₂ concentrations, with higher levels observed during the dry season, particularly in DJF. Areas with intense biomass burning activity exhibit significantly elevated NO₂ levels, indicating a strong relationship between fire emissions and air pollution. Urban regions also show consistently high NO₂ concentrations.

## Conclusion

This study highlights the impact of biomass burning on air quality in West Africa and emphasizes the importance of monitoring seasonal pollution trends. The findings provide insight into environmental and public health implications, supporting future research and policy development.

## How to Run

Clone the repository, install the required dependencies, and run the provided scripts or notebooks to reproduce the analysis and visualizations.
