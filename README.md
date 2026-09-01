# MMFR Mangrove Dynamics, 1993-2023

## Three Decades of Mangrove Extent, Canopy Dynamics and Water-Edge Exposure in Matang, Malaysia

This repository contains reproducibility materials for a Landsat-based
assessment of long-term mangrove dynamics in the Matang Mangrove Forest Reserve
(MMFR), Malaysia.

The study integrates:
1. four-epoch mangrove mapping for 1993, 2003, 2013 and 2023;
2. repeated exact-year external product agreement with CGMD;
3. annual within-mangrove canopy-condition trajectories;
4. 1993-2023 gain/loss transitions and water-edge exposure;
5. conservative environmental-context and sensitivity analyses.

## Workflow

**Google Earth Engine** -> Landsat preprocessing, spectral predictors, Random
Forest mapping, annual canopy metrics and geospatial exports.

**Google Colab / Python** -> CGMD external agreement, trend analysis, transitions,
water-edge exposure, environmental sensitivity, final figures and tables.

## Google Earth Engine

https://code.earthengine.google.com/0be1f812eac679d252b0cd741fa382a2

## Main scientific notebook

`notebooks/MMFR_analysis_pipeline.ipynb`

## Large raster data

**[Download the complete MMFR raster package from Google Drive](https://drive.google.com/drive/folders/12xsJ0O_-dnXbGPHxIg4j85hOWCGSSPj6?usp=sharing)**

The package contains 19 GeoTIFF files grouped into core derived products,
RF hard-class maps, predictor stacks and Landsat composites. A complete
inventory is provided in `data/external_rasters/raster_manifest.csv`.
## Important interpretation

The CGMD comparison is reported as **external product agreement**, not as
field-ground-truth classification accuracy.

## Authors

- Nurhafizul Abu Seri
- Arrafi Malika Ardy
