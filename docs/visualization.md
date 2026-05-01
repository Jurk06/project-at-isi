---
layout: page
title: Visualization & Geographic Analysis
permalink: /visualization/
---

# Visualization & Geographic Mapping

## Overview

This section showcases the geographic analysis of water wells across India. Using latitude and longitude coordinates from the dataset, wells are plotted on the Indian administrative map to visualize spatial distribution and identify regional patterns.

![Well location sample from the dataset]({{ site.baseurl }}/images/image01.png)
*Figure: Sample image loaded from the project's `images` folder to provide additional analytic context.*

## Key Visualizations

### 1. Well Distribution Map
- Interactive map of all wells across Indian states
- Color-coded by well depth categories
- Identifies high-risk and low-risk regions

### 2. Well Depth Analysis
- State-wise distribution of well depths
- Box plots showing median and variation by region
- Identification of anomalies and outliers

### 3. Regional Patterns
- Concentration of wells in different states
- Correlation with water availability metrics
- Geographic clustering indicators

## Data Used

- **Latitude & Longitude**: Precise well locations
- **Well Depth**: Primary indicator of water table depth
- **Admin Boundaries**: India state shapefile (`india_administrative_state_boundary.shp`)

## Key Findings

- Wells vary significantly in depth across different geographic regions
- Coastal and riverine areas show different depth patterns compared to inland regions
- Some states show clustering of wells, indicating intensive monitoring

## Interactive Maps

The analysis includes interactive folium maps that allow:
- Zooming and panning across India
- Hovering for well details
- Filtering by depth ranges

## Notebook

Full visualization code available in: `indian-map.ipynb`

### References
- [Kaggle Visualization](https://www.kaggle.com/jurk06/indian-map#Well-depth-Analysis)
