# Spatial Analysis & Land Cover Classification with QGIS

## Overview
This repository contains geospatial analysis projects developed using QGIS, focusing on Remote Sensing, environmental monitoring, and land cover classification. The primary objective is to demonstrate practical workflows for satellite imagery processing and spatial intelligence.

---

## Featured Project: NDVI & Supervised Land Cover Classification

### Objective
To analyze vegetation health and map land use/land cover (LULC) changes using satellite imagery processed through spectral index calculations and machine learning classification algorithms.

### Methodology & Tools
* **Software:** QGIS (v3.x)
* **Plugins Used:** Semi-Automatic Classification Plugin (SCP) / Dzetsaka
* **Data Sources:** Sentinel-2 / Landsat 8 multispectral imagery
* **Workflow Steps:**
  1. **Preprocessing:** Band composition, atmospheric correction, and subsetting to the area of interest (AOI).
  2. **Spectral Index Calculation:** Normalized Difference Vegetation Index (NDVI) generated using Raster Calculator ($NDVI = \frac{NIR - Red}{NIR + Red}$).
  3. **Supervised Classification:** ROI (Region of Interest) collection and training sample generation across distinct land cover classes (e.g., Urban, Dense Vegetation, Sparse Vegetation, Water Bodies).
  4. **Post-Processing:** Accuracy assessment, class aggregation, and final cartographic map layout generation.

---

## Results & Visualizations

### 1. NDVI Map
![NDVI Analysis](img/ndvi_map.png)
*Figure 1: Normalized Difference Vegetation Index showcasing spatial distribution of photosynthetic activity.*

### 2. Land Cover Classification
![Supervised Classification](img/classification_map.png)
*Figure 2: Supervised classification output dividing the region into target environmental categories.*

---

## Key Insights
* **Vegetation Density:** High NDVI values (> 0.6) highlight healthy, dense canopy areas, predominantly concentrated in protected zones.
* **Urban Sprawl:** The classification model effectively distinguished built-up surfaces from bare soil and sparse vegetation.
* **Accuracy:** Overall accuracy achieved acceptable confidence thresholds for regional environmental monitoring.

---

## Contact & Profile
**Renato** — Geographer & GIS Analyst  
*Specializing in Geoprocessing, Spatial Analysis & Remote Sensing.*  
[LinkedIn Profile](https://linkedin.com) | [GitHub Profile](https://github.com/renatodb)
