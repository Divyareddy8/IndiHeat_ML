# Urban Heat Island Study Across Indian Metro Cities

A multi-city Surface Urban Heat Island (SUHI) analysis across major Indian metropolitan regions using satellite remote sensing, geospatial analysis, and machine learning.

## Overview

This project analyses Urban Heat Island (UHI) patterns across:

- Delhi
- Mumbai
- Bengaluru
- Chennai
- Kolkata
- Hyderabad
- Ahmedabad
- Pune

The study investigates how rapid urbanisation, impervious surfaces, vegetation loss, industrial activity, and land-use change influence urban warming across different climatic and geographic settings in India.

The analysis combines:

- Google Earth Engine
- Landsat 8/9
- MODIS
- Sentinel-2
- Sentinel-5P TROPOMI
- ESA WorldCover
- WorldPop
- SRTM DEM

## Objectives

- Analyse daytime and nighttime Surface Urban Heat Island intensity
- Compare UHI patterns across multiple Indian metro cities
- Identify thermal hotspots and cooling zones
- Study the influence of vegetation, built-up density, water bodies, and air quality
- Apply machine learning models with SHAP-based interpretability to identify key UHI drivers

## Methodology

The workflow includes:

- Landsat preprocessing and cloud masking
- Land Surface Temperature (LST) extraction
- Spectral index generation (NDVI, NDBI, NDWI, SAVI, EVI, etc.)
- Local Climate Zone (LCZ) analysis
- Nighttime UHI estimation using MODIS
- Air-quality feature extraction using Sentinel-5P
- Machine learning modelling using:
  - Random Forest
  - XGBoost
  - MLP Neural Network
- SHAP explainability for feature importance analysis

## Key Findings

- Dense impervious urban regions consistently show the highest UHI intensity.
- Vegetation, wetlands, lakes, and river corridors act as major urban cooling zones.
- Coastal cities show moderated daytime heating but strong localised hotspots.
- Rapid IT-led expansion and industrial growth strongly influence warming patterns.
- Loss of blue-green infrastructure is a common driver across all cities.

## Study Period

2019–2023 (multi-year median composites)

## Platforms used

- Google Earth Engine
- QGIS

