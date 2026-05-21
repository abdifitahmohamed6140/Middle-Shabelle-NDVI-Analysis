# NDVI-Based Vegetation Condition Assessment of Middle Shabelle, Somalia (2025)

## Project Overview
This GIS and remote sensing project analyzes vegetation conditions in the Middle Shabelle region of Somalia using the Normalized Difference Vegetation Index (NDVI) derived from Landsat 8/9 satellite imagery.

The project was conducted using QGIS to process satellite imagery, calculate NDVI values, classify vegetation conditions, and produce a final thematic vegetation map.

The analysis helps demonstrate how remote sensing and GIS techniques can be used for environmental monitoring, vegetation assessment, drought analysis, and agricultural planning in Somalia.

---

# Objectives
The main objectives of this project were:

- Assess vegetation conditions in Middle Shabelle
- Identify areas of dense and sparse vegetation
- Apply NDVI techniques using Landsat imagery
- Demonstrate practical GIS and remote sensing workflows
- Produce a professional vegetation condition map

---

# Study Area
The study area is Middle Shabelle, located in southern Somalia.

Middle Shabelle is an important agricultural region influenced by the Shabelle River system. The region contains irrigated agricultural areas, dry lands, and varying vegetation conditions that make it suitable for NDVI-based environmental analysis.

---

# Data Used

| Dataset | Description |
|---|---|
| Landsat 8/9 Imagery | Satellite imagery downloaded from USGS EarthExplorer |
| Band 5 (NIR) | Near Infrared band used for vegetation detection |
| Band 4 (Red) | Red spectral band used in NDVI calculation |
| Middle Shabelle Boundary | Shapefile used for clipping the study area |
| QGIS 3.x | GIS software used for processing and map production |

---

# Data Sources
- USGS EarthExplorer
- USGS Landsat Missions
- QGIS Official Website

---

# Software Used
- QGIS 3.x

---

# Methodology

## 1. Data Preparation
Landsat 8/9 imagery covering the study area was downloaded from the USGS EarthExplorer platform.

The following raster bands were loaded into QGIS:
- Band 5 (Near Infrared)
- Band 4 (Red)

A Middle Shabelle boundary shapefile was also prepared for spatial clipping.

---

## 2. NDVI Calculation
NDVI was calculated in QGIS using the Raster Calculator tool with the following formula:

```text
NDVI = (NIR - Red) / (NIR + Red)
```

Where:
- NIR = Band 5
- Red = Band 4

NDVI values help distinguish healthy vegetation from sparse vegetation, bare surfaces, and water bodies.

---

## 3. Raster Clipping
The resulting NDVI raster was clipped using the Middle Shabelle boundary shapefile to extract only the study area.

This step improves map accuracy and removes unnecessary surrounding areas.

---

## 4. NDVI Classification
The NDVI raster was classified into five vegetation categories.

| NDVI Range | Vegetation Class |
|---|---|
| < -0.3 | Water / Bare Surface |
| -0.3 – 0.0399 | Very Low Vegetation |
| 0.0399 – 0.1891 | Sparse Vegetation |
| 0.1891 – 0.3383 | Moderate Vegetation |
| > 0.3383 | Dense Vegetation |

Different color symbols were applied in QGIS for visualization.

---

## 5. Map Layout Design
The final map layout was prepared in QGIS and included:
- Title
- Legend
- North Arrow
- Scale Bar
- Data Source Information

---

# Results and Discussion
The final NDVI map showed different vegetation conditions across Middle Shabelle.

Areas close to the Shabelle River and agricultural zones showed moderate to dense vegetation represented by green colors. These areas are likely supported by irrigation activities and higher soil moisture availability.

Large parts of the region showed sparse and very low vegetation represented by yellow and orange colors, indicating dry environmental conditions and lower vegetation density.

Some water and bare surface areas were identified using dark red colors.

The analysis demonstrates how vegetation distribution in Middle Shabelle is strongly influenced by water availability and land use patterns.

---

# Final Output

## NDVI Vegetation Condition Map
![NDVI Map](Middle_Shabelle_NDVI_Map.jpeg)

---

# Skills Demonstrated
This project demonstrates practical skills in:

- Remote Sensing
- GIS Analysis
- NDVI Analysis
- Raster Processing
- Spatial Data Management
- Cartography
- Environmental Mapping
- QGIS Workflow

---

# Project Files
This repository contains:
- NDVI map outputs
- Shapefiles
- Raster datasets
- Project documentation
- GIS processing files

---

# Author
## Abdifitah Mohamed Abdullahi

Environmental and GIS Research Projects | QGIS | Remote Sensing | Somalia

GitHub Portfolio Project — 2025
