# Econometric Analysis of Slum Population  

## Overview
This repository contains my **Econometrics** class project analyzing the socio-economic factors affecting the proportion of populations living in slums across various countries. The analysis uses **descriptive statistics, histograms, and econometric regressions** to explore relationships between slum prevalence and variables such as:

- Proportion of refugees in a country  
- GDP per capita  
- Income inequality  
- Urbanization  

A key contribution of this project was creating a new variable, `percent_refugees`, which measures the proportion of refugees relative to total population, and applying both **fixed effects** and **pooled OLS regressions** to examine how these factors impact urban slum conditions.

---

##  Methods and Analysis
- **Data Preparation:**  
  - Constructed `percent_refugees` = refugees / total population.  
  - Examined distributions of key variables (GDP, Gini coefficient, refugee count) and addressed skewness observed in the data.  

- **Descriptive Analysis:**  
  - Produced tables of descriptive statistics.  
  - Visualized histograms for unemployment rates, GDP per capita, and proportion of urban population living in slums.  
  - Noted patterns such as skewness, peaks, and variation across countries.  

- **Econometric Modeling:**  
  - **Fixed Effects Regression:** Controlled for unit-specific and time-specific effects. Highlighted the significant impact of year dummies and the proportion of refugees (`percent_refugees`) on slum prevalence.  
  - **Pooled OLS Regression:** Explored models with multiple regressors, highlighting potential issues of overfitting and multicollinearity.  
  - Compared results to understand the robustness of findings and the impact of model choice on interpreting socio-economic relationships.  

---

## Key Findings
- The mean proportion of the urban population living in slums was **53.2%**, with high variation across countries.  
- `percent_refugees` was a significant predictor, suggesting that increases in refugee populations contribute substantially to slum prevalence.  
- Fixed effects models provided more reliable estimates by controlling for temporal and unit-specific factors.  
- Pooled OLS models were sensitive to overfitting and multicollinearity, especially in models with many regressors.  
- Insights highlight the importance of economic variables like GDP, income distribution, and urbanization in understanding slum growth.

