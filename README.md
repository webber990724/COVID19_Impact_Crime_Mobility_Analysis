# COVID19 Impact on Crime and Mobility in London  
**License**: ODbLv1.0  

**Lifecycle**: stable  

GitHub Stars | Issues | Release Activity | Commit Activity | Last Commit  

## **Overview**  
**COVID19 Impact on Crime and Mobility in London** is an open code product designed for spatio-temporal analysis of crime and mobility data during the COVID-19 lockdowns in London. This repository includes:  
- **Data**: Crime data, mobility statistics, and geographic boundaries.  
- **Code**: Python-based Jupyter Notebook for data cleaning, analysis, and visualization.  
- **Analysis**: Evaluation of changes in crime rates, mobility patterns, and their correlation during lockdowns.  

This project supports researchers, urban planners, and policymakers in understanding the pandemic's impact on urban dynamics.  

---

## **Data Description**  
This project includes multiple data sets related to London's crime and mobility patterns:  

### **Crime Data**  
- Sources: Metropolitan Police Service and open crime databases.  
- Files:  
  - `MPS_LSOA_Level_Crime_1218-1120.csv` (Dec 2018–Nov 2020)  
  - `MPS_Borough_Level_Crime_Historic.csv` (Jan 2008–Dec 2018)  
- Features: Crime category, monthly crime rates, spatial identifiers (LSOA).  

### **Mobility Data**  
- Sources: Google mobility reports.  
- Files:  
  - `mobility_p3.csv` (Oct 31–Dec 2, 2020)  
- Features: Mobility change percentages across boroughs, categories like parks and retail.  

### **Geographic Boundaries**  
- Sources: OpenStreetMap and GeoJSON files.  
- Files:  
  - `London.shp`  
  - `Borough_cases_mobility.shp`  

---

## **Code Description**  
The Jupyter Notebook includes:  
1. **Exploratory Data Analysis**:  
   - Visualization of COVID-19 cases and mobility patterns.  
   - Comparative analysis of crime trends during lockdown periods.  

2. **Spatio-temporal Analysis**:  
   - Geographic crime pattern visualization using `geopandas`.  
   - Temporal trend analysis for various crime types.  

3. **Modeling and Regression**:  
   - Geographically Weighted Regression (GWR) to assess spatial heterogeneity in crime rates.  

4. **Clustering**:  
   - DBSCAN for clustering low-level geographies (LSOA).  

---
