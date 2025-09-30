# Life Expectancy and GNI per Capita Analysis

## 📌 Project Overview
This project explores the relationship between **Gross National Income (GNI) per capita**, **population**, and **life expectancy** across different countries and years.  
The goal is to analyze whether higher income levels are associated with longer life expectancy, and how population size might influence these patterns.
## File overview
- **eda_template.ipynb**: Main notebook containing the exploratory data analysis (EDA), data cleaning, transformations, and visualizations.  
- **Project Presentation (PowerPoint)**: Slide deck presenting the project results and insights for a non-technical audience.  
- **world-development-statistics/**: Folder containing the three datasets used in the project:
  - `gni_per_cap_atlas_method_con2021.csv` (GNI per capita data)  
  - `population.csv` (population data)  
  - `life_expectancy.csv` (life expectancy data) 
## 📊 Dataset
The project contain following datasets :
- gni_per_cap_atlas_method_con2021.csv: contain GNI per capita (in usd dollar) per country data from 1800 to 2050 
- population.csv: contain population data per country from 1800 to 2100
- life_expectancy.csv: contain life expectancy per country from 1800 to 2100

## 🔍 Methodology
1. **Exploratory Data Analysis (EDA)**
   - Summary statistics for all variables  
   - Visualization of trends across years and countries  
   - Scatter plots to examine the relationship between GNI per capita and life expectancy  
   - Bubble charts to include the effect of population  
   - Correlation analysis  
2. **Data Cleaning & Preparation**
   - Handled missing values and duplicates  
   - Converted columns into appropriate data types  
   - Combined multiple sources into a single dataset  

3. **Visualization**
   - Line plots for trends across time  
   - Scatter plots with regression lines  
   - Bubble plots (GNI vs. life expectancy with population size)  
   - Heatmaps for correlations  
## Requirement
Run this script to install requirement of the project
```bash
pip install pandas numpy matplotlib seaborn scipy
```
