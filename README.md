# Comprehensive Geospatial Health Risk Analysis Using Python

This project presents a multi-dimensional analysis of public health data through geospatial and statistical techniques. The goal is to uncover patterns in disease prevalence and environmental vulnerability, and provide actionable insights for targeted healthcare policy and interventions. The entire analysis is conducted using Python with extensive data visualizations and modeling.

## Project Tasks and Highlights

### 1. LISA Analysis on Heart Disease Cases
- Applied Global and Local Moran's I to detect spatial autocorrelation in heart disease cases.
- Identified hotspots, cold spots, and outliers using LISA Cluster Maps.
- **Conclusion**: Heart disease cases show a largely random distribution, with a few significant clusters warranting policy attention.

### 2. Climate Health Vulnerability Index (CHVI)
- Constructed a composite index combining environmental risks, population sensitivity, and adaptive capacity.
- CHVI enabled spatial ranking of regions based on climate-health risk exposure.
- **Recommendation**: Strengthen healthcare and improve environmental resilience in high-risk regions.

### 3. Malaria and Dengue Hotspot Detection
- Performed Getis-Ord Gi\* hotspot analysis with rainfall and temperature data.
- Used logistic regression to model disease outbreaks.
- **Finding**: Rainfall significantly influences malaria, while dengue has a more dispersed pattern, independent of high rainfall.

### 4. Child Malnutrition and Environmental Factors
- Explored correlation and linear regression with soil moisture, humidity, and temperature.
- **Results**: No significant linear relationship.
- Suggests malnutrition is better explained by **socioeconomic** factors than environmental ones.

### 5. Tuberculosis and Population Density
- Used Negative Binomial Regression to analyze TB cases.
- Found a **positive correlation** between population density and TB prevalence.
- **Recommendations**: Expand predictors and use advanced models to handle overdispersion and improve fit.

## Tools & Libraries Used
- Python: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Statsmodels`, `Geopandas`
- Spatial statistics: `PySAL`, `LISA`, `Moran’s I`, `Getis-Ord Gi*`
- Machine learning: Logistic & Linear Regression
- Geospatial visualization: `QGIS`, `GeoPandas`, `KDE` plots

## Recommendations
- Prioritize targeted interventions in high-risk clusters.
- Integrate environmental monitoring with public health planning.
- Expand models using additional socioeconomic indicators.
- Use this analytical pipeline to support data-driven health policy in other domains.

## Author
**Shalvi Singh**  
singhshalvi668@gmail.com  

