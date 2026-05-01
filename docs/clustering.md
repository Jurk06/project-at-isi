---
layout: page
title: Clustering Analysis
permalink: /clustering/
---

# Well Clustering Analysis

## Overview

This section presents **hierarchical clustering** analysis that groups wells based on their characteristics, particularly well depth and water availability patterns. This helps identify distinct categories of wells and regions with similar hydrological properties.

## Methodology

### Clustering Approach
- **Algorithm**: Hierarchical Clustering (Divisive Method)
- **Distance Metric**: Euclidean distance
- **Linkage Method**: Ward linkage
- **Features**: Well depth, water availability metrics, effort metrics

### Two Clustering Strategies

#### 1. Feature-Based Clustering
Groups wells by their hydro-geological characteristics:
- Similar well depths
- Comparable water availability
- Related effort metrics

#### 2. Geographic-Based Clustering
Divides wells by geographic proximity and regional characteristics:
- Distance-based clustering
- Regional water table patterns
- State-wise water resource distribution

## Results

### Risk Categories

Wells are classified into **multiple clusters** representing:
- **High-Risk**: Deep wells with declining water tables
- **Medium-Risk**: Moderate depth with mixed trends
- **Low-Risk**: Shallow wells with stable water availability

### Geographic Segments

Regions cluster into groups with similar:
- Hydrological characteristics
- Water stress levels
- Required intervention strategies

## Dendrograms

Hierarchical clustering visualizations show:
- Merge patterns at different distance thresholds
- Natural groupings of wells
- Geographic and feature-based relationships

## Applications

✓ **Risk Management**: Prioritize intervention in high-risk clusters  
✓ **Resource Planning**: Tailor strategies by cluster type  
✓ **Policy Making**: Inform regional water management policies  
✓ **Predictive Analysis**: Use clusters for forecasting  

## Key Insights

- Clear separation between well-depth based groups
- Geographic proximity correlates with hydro-geological similarity
- Some inter-state regions show similar patterns despite distance
- Clustering reveals hidden regional water stress relationships

## Interactive Analysis

- Dendrogram visualization with clickable nodes
- 2D/3D scatter plots of well clusters
- Geographic maps showing cluster distribution

## Notebooks

- `clustering_of_well_data.ipynb` - Main clustering analysis
- [Google Colab - Full Interactive Analysis](https://colab.research.google.com/drive/1qAO2AvGzeaz2ozA63z8BkLNZw1-mfiUF?usp=sharing)

### References
- Hierarchical clustering: Johnson, S. C. (1967). Hierarchical clustering schemes
- Distance-based methods in spatial analysis
