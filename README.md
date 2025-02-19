# Electricity Consumption Analysis: Python & Tableau
[![Tableau Dashboard](https://github.com/TiffanyNwanne/Electricity-Consumption-Analysis/blob/main/images/Residential%20Sector.png))](https://public.tableau.com/app/profile/tiffany.nwanne/viz/ElectricityConsumptionAnalysis_17379088123250/ResidentialSector)

## Overview
This project explores electricity consumption trends using Python for data analysis and Tableau for visualization. I examined how energy demand has changed over time, calculate Year-over-Year (YoY) growth, and assess how residential, Commercial, Industrial, and Transportation sectors contribute to total revenue, identify growth patterns, and use forecasting techniques to redict future electricity demands. 

## Python

**Dataset Summary**

The dataset contains electricity sales data across four key sectors:
+ Residential
+ Commercial
+ Industrial
+ Transportation

### Data Cleaning & Preprocessing

[![Preview Image](https://github.com/TiffanyNwanne/Electricity-Consumption-Analysis/blob/main/images/EIA%20Data%20Preparation.png))](https://github.com/TiffanyNwanne/Electricity-Consumption-Analysis/blob/main/images/EIA%20Data%20Preparation.png)

Before analysis, I:
+ Removed unnecessary headers and missing values
+ Converted columns to numerical types
+ Calculated Year-over-Year (YoY) growth
+ Computed sector contribution percentages

### Data Analysis

[![Preview Image](https://github.com/TiffanyNwanne/Electricity-Consumption-Analysis/blob/main/images/EIA%20Analysis%201.png))](https://github.com/TiffanyNwanne/Electricity-Consumption-Analysis/blob/main/images/EIA%20Analysis%201.png)

[![Preview Image](https://github.com/TiffanyNwanne/Electricity-Consumption-Analysis/blob/main/images/EIA%20Analysis%202.png))](https://github.com/TiffanyNwanne/Electricity-Consumption-Analysis/blob/main/images/EIA%20Analysis%201.png)


### Forecasting Future Electricity Demand With Prophet

[![Preview Image](https://github.com/TiffanyNwanne/Electricity-Consumption-Analysis/blob/main/images/Forecasting%20Code%2010.png))}(https://github.com/TiffanyNwanne/Electricity-Consumption-Analysis/blob/main/images/Forecasting%20Code%2010.png)

To predict energy trends for the next 10 years, I applied Facebook Prophet in Python:

[![Preview Image](https://github.com/TiffanyNwanne/Electricity-Consumption-Analysis/blob/main/images/Eectricitv%20Sales%20Forecast%20(A%20Sectors).png))](https://github.com/TiffanyNwanne/Electricity-Consumption-Analysis/blob/main/images/Eectricitv%20Sales%20Forecast%20(A%20Sectors).png)

Key Forecasting Takeaways:
+ Electricity demand is projected to grow, with Commercial leading the expansion.
+ Industrial sector remains volatile, reflecting economic uncertainty.
+ Transportation demand will rise, driven by EV adoption and infrastructure growth.

## Tableau
To summarize insights, I built a KPI dashboard with three key indicators:

[![Preview Image](https://github.com/TiffanyNwanne/Electricity-Consumption-Analysis/blob/main/images/Tableau%20KPIS.png))](https://github.com/TiffanyNwanne/Electricity-Consumption-Analysis/blob/main/images/Tableau%20KPIS.png)

+ 1️⃣ Total Electricity Sales (GWh) – Displays total energy consumption per year.
+ 2️⃣ YoY Growth (%) – Highlights whether electricity demand is rising or falling.
+ 3️⃣ Largest Contributing Sector – Identifies which sector contributes the most to overall revenue.

## Business Impact & Key Takeaways
This project provided critical insights for decision-makers in the energy sector:

+ ✔ Identified the Residential sector as the fastest-growing revenue driver.

+ ✔ Helped optimize pricing strategies by sector.

+ ✔ Used predictive modeling to improve financial planning.

+ ✔ Built a real-time Tableau dashboard for monitoring revenue trends.







