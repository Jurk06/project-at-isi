---
layout: default
title: Water Well Riskiness Analysis
---

# Analysis of Water Well Riskiness Across India

## 🌍 Project Overview

This project analyzes the **riskiness of wells across different states of India** to identify which wells are most prone to water scarcity. As the world faces a severe water crisis, understanding the reliability of water sources is critical—especially in India where wells are a primary source of drinkable water.

### Key Objectives
- Identify high-risk wells prone to water scarcity
- Analyze water table depth trends across Indian states
- Impute missing data using advanced statistical techniques
- Cluster wells by risk level and geographic region

---

## 📊 Analysis Workflow

### 1. [Data Preprocessing & ANOVA Analysis]({{site.baseurl}}/anova)
Statistical analysis to identify significant differences between independent variables and features across different states.

### 2. [Visualization & Geographic Analysis]({{site.baseurl}}/visualization)
Interactive mapping of wells across India using latitude/longitude data, with visualizations of well depths and regional variations.

### 3. [Missing Data Imputation]({{site.baseurl}}/imputation)
Advanced multiple imputation techniques to handle missing values based on data distribution patterns.

### 4. [Trend Analysis]({{site.baseurl}}/trends)
Historical analysis of water table depth trends over time to understand long-term patterns.

### 5. [Clustering Analysis]({{site.baseurl}}/clustering)
Hierarchical clustering to identify well groups based on depth and risk factors, segmented by geographic region.

---

## 📁 Project Structure

```
project-at-isi/
├── clustering_of_well_data.ipynb          # Clustering analysis
├── Effort_and_Arrival.ipynb               # Temporal analysis
├── indian-map.ipynb                       # Geographic visualization
├── Missing_Data_has_3_categories.ipynb    # Imputation methods
├── data.csv                               # Main dataset
├── india_administrative_state_boundary.*  # Shapefile for mapping
└── README.md                              # Full documentation
```

---

## 📈 Key Findings

- **Missing Data**: A significant portion of data was missing, requiring sophisticated imputation techniques
- **Regional Variation**: Well depth and water availability vary significantly across states
- **Risk Clustering**: Wells cluster into distinct risk categories based on depth and historical trends
- **Trend Analysis**: Long-term trends reveal critical patterns in water table decline

---

## 🔧 Technologies Used

- **Python** for data analysis
- **Pandas** for data manipulation
- **Scikit-learn** for clustering and imputation
- **Matplotlib & Seaborn** for visualization
- **Folium** for geographic mapping

---

## 📚 Additional Resources

- **Blog Post**: [Visualization and Multiple Imputation](https://rabkumarisinghisikolkata.medium.com/visualization-and-multiple-imputation-734b9e73f2b2)
- **Kaggle Datasets**: [ANOVA Analysis](https://www.kaggle.com/jurk06/) | [Indian Map Visualization](https://www.kaggle.com/jurk06/indian-map)
- **Dataset**: Atal Jal water well data (31 March 2021)

---

## 👤 Author

**Rab Kumari Singh**  
*ISI Kolkata*

For questions or collaboration, feel free to reach out!
