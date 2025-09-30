# Life Expectancy and GNI per Capita Analysis

## 📌 Project Overview
This project explores the relationship between **Gross National Income (GNI) per capita**, **population**, and **life expectancy** across different countries and years.  
The goal is to analyze whether higher income levels are associated with longer life expectancy, and how population size might influence these patterns.
## 🔹 Problem Statement

While global life expectancy has risen significantly since the 19th century, inequalities in health and wealth persist across countries and regions. Wealthier nations generally enjoy longer lives, but the relationship is not always straightforward. At lower income levels, small increases in wealth can dramatically improve health outcomes, while at higher income levels, gains in longevity tend to plateau.

This raises several questions:
- How strongly are income and life expectancy related over time?

- Do all regions follow the same pattern, or are there clear exceptions?

- What role does population growth play in shaping these trends?

- Can improvements in life expectancy be explained solely by income, or do other factors (policy, healthcare, social systems) play a critical role?

By addressing these questions, this project seeks to uncover patterns in the relationship between economic development, health, and population — and to provide evidence-based insights into why some regions thrive while others continue to lag behind.
## File overview
- **World_development_Analysis.ipynb**: Main notebook containing the exploratory data analysis (EDA), data cleaning, transformations, and visualizations.  
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
## 📌 Conclusion

*From our analysis of GNI per Capita, Population, and Life Expectancy (1800–2050) across countries like USA, Japan, Brazil, India, Nigeria, and Ethiopia:*

__1. Strong correlation between wealth and health__
- Countries with higher GNI per capita (USA, Japan) consistently achieve higher life expectancy.
- However, after a certain point (~$30,000), wealth brings diminishing returns — lifestyle and healthcare quality matter more.

__2. Population dynamics shape economic outcomes__
- Fast-growing populations (India, Nigeria, Ethiopia) make it difficult to raise average income (GNI per capita).
- In contrast, slower population growth in Japan and USA has supported sustained wealth per person.

__3. Health improvements drive long-term growth__
- Countries that invested in healthcare and education earlier (Japan, USA) gained not only longer lives but also more productive economies.
- Late starters (Nigeria, Ethiopia) show progress but still lag in both wealth and life expectancy.
## Requirement
You need to have a working python 3.x machine and install following packages to run the project

**Main Python libraries used in this project:**
- pandas
- numpy
- matplotlib
- seaborn
- scipy

Run this script to install requirement of the project
```bash
pip install pandas numpy matplotlib seaborn scipy
```
