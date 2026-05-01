---
layout: page
title: About This Project
permalink: /about/
---

# About This Project

## Context

This water well analysis project was conducted at **ISI Kolkata** (Indian Statistical Institute) in collaboration with Prof. A.B. and focuses on understanding water scarcity patterns across India.

## Motivation

The project addresses a critical global issue:
- **World Water Crisis**: Increasing scarcity of drinkable water
- **India's Dependency**: Heavy reliance on groundwater through wells and ponds
- **Policy Need**: Understanding well reliability to inform water management decisions

## Research Questions

1. Which wells are most at risk of water scarcity?
2. How does water table depth vary across Indian states?
3. What temporal trends can help predict future water availability?
4. Can we cluster wells into risk categories for targeted intervention?

## Dataset

**Source**: Atal Jal (National Water Conservation and Augmentation Mission)  
**Collection Date**: March 31, 2021  
**Scope**: Comprehensive water well measurements across Indian states  
**Variables**: Location (lat/long), depth, availability metrics, temporal measurements

### Data Characteristics
- Multiple years of historical measurements
- Geographic coverage across India's states
- Missing data requiring advanced imputation techniques
- Rich temporal dimension for trend analysis

## Methodology

This project employs a rigorous data science workflow:

1. **Data Cleaning**: Handling missing values and inconsistencies
2. **Exploratory Analysis**: ANOVA tests for statistical differences
3. **Visualization**: Geographic mapping and regional analysis
4. **Imputation**: Advanced MICE techniques for missing data
5. **Trend Analysis**: Temporal pattern identification
6. **Clustering**: Risk categorization and regional grouping

## Key Contributions

✓ Identifies high-risk well regions requiring urgent intervention  
✓ Provides data-driven insights for policy makers  
✓ Demonstrates advanced imputation techniques  
✓ Enables predictive modeling for water availability  

## Team

- **Primary Researcher**: Rab Kumari Singh
- **Advisor**: Prof. A.B., ISI Kolkata
- **Institution**: Indian Statistical Institute, Kolkata

## References

- Blog: [Visualization and Multiple Imputation](https://rabkumarisinghisikolkata.medium.com/visualization-and-multiple-imputation-734b9e73f2b2)
- Kaggle Profile: [Jurk06](https://www.kaggle.com/jurk06)
- Dataset: [Atal Jal Water Well Data](https://data.gov.in)

## How to Use This Site

Navigate through the analysis sections to explore:
- [Statistical analysis (ANOVA)]({{site.baseurl}}/anova)
- [Geographic visualizations]({{site.baseurl}}/visualization)
- [Imputation methodology]({{site.baseurl}}/imputation)
- [Temporal trends]({{site.baseurl}}/trends)
- [Clustering results]({{site.baseurl}}/clustering)

---

*This website is built with Jekyll and hosted on GitHub Pages for transparent, reproducible research.*
