# Bike Rental Demand Analysis & Forecasting

This project analyzes how weather conditions, holidays, and seasonal patterns influence bike‑rental demand using an R‑based workflow. The analysis includes data cleaning, exploratory visualization, seasonal decomposition, and ARIMA forecasting, with results shared through an HTML report.

---

## Project Overview
- Cleaned and transformed bike‑rental and weather datasets, including reversing encoded categorical features back to their original observational names
- Explored daily, weekly, and seasonal demand patterns  
- Assessed the impact of temperature, precipitation, and holidays  
- Visualized trends using ggplot2  
- Applied ARIMA models (via the **tseries** package) for monthly demand forecasting  
- Exported the full analysis as an HTML report for easy sharing and presentation  

---

## Tools & Libraries (R)
- **tidyverse** (dplyr, tidyr, readr)  
- **ggplot2** for visualizations  
- **tseries** for ARIMA modeling  
- **forecast** 
- **knitr / rmarkdown** for generating the HTML report  

---

## Key Insights
- Weather strongly influences daily rental volume  
- Holidays and weekends show distinct usage patterns  
- Clear seasonal structure with summer peaks and winter lows  
- ARIMA models provide actionable monthly demand forecasts  
