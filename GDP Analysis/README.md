## Overview

This project analyzes India's GDP and economic growth trends, focusing on the composition of GDP, sectoral contributions (Agriculture, Industry, Services), and the influence of macroeconomic factors such as inflation, foreign investment, government policy, and population growth. The analysis leverages a time-series dataset to explore economic indicators, their relationships, and their impact on India's economic development. The project is implemented in a Jupyter Notebook (GDP_Analysis.ipynb) using Python for data cleaning, exploratory data analysis (EDA), and visualization.
## Objectives

* Analyze India’s GDP trends, including Nominal GDP, Real GDP, and annual growth rates.

* Examine sectoral contributions (Agriculture, Industry, Services) to GDP over time.

* Investigate the impact of exports, imports, and FDI inflows on GDP growth, trade balance, and currency reserves.

* Assess the effects of fiscal deficit, public debt, and repo rate changes on economic growth and inflation.

* Study the relationship between population growth, poverty rate, household consumption, and economic development.

## Dataset

The dataset is a time-series collection of India’s economic indicators, including:
## Economic Growth Indicators:
* GDP (Nominal): Total economic output without inflation adjustment (in billions, likely USD or INR).
* GDP (Real): Inflation-adjusted GDP.
* GDP Growth (annual %): Year-over-year growth rate.
* Sectoral Contributions (% of GDP):
* Agriculture Contribution
* Industry Contribution
* Services Contribution
* External Trade:
* Exports (% of GDP)
* Imports (% of GDP)
## Investment and Capital:
* FDI Inflows (% of GDP)
* Gross Fixed Capital Formation (% of GDP)
* Private Sector Credit (% of GDP)
## Government Finances:
* Fiscal Deficit (% of GDP)
* Public Debt (% of GDP)
* Government Revenues (% of GDP)
* Tax Revenue (% of GDP)
## Monetary Policy:
* Repo Rate: Central bank’s interest rate policy.
## Social and Economic Indicators:
* Population Growth Rate (annual %)
* Poverty Rate (%)
* Household Consumption Expenditure (% of GDP)
* Energy Consumption per Capita (kWh)
* Unemployment Rate (%)
* Inflation CPI: Consumer Price Index-based inflation rate.
* Oil Rents (% of GDP)

## Tools/Libraries: 
 Pandas, NumPy, Seaborn, Matplotlib, Jupyter Notebook.

## Analysis Steps
## Data Import:
* Load the dataset into a Pandas DataFrame using pd.read_csv() or similar.
## Data Cleaning:
* Handle missing values and renaming columns for simplicity.
## Data Transformation:
* Standardize/scale numerical columns for consistency.
## Feature Engineering:
* Create derived features like GDP per capita or year-over-year changes in key indicators.
## Exploratory Data Analysis (EDA):
* Analyze GDP trends, sectoral contributions, and relationships with macroeconomic factors.
* Investigate fiscal, trade, and social indicators’ impact on economic growth.

## Visualizations: 
* Scatterplot (Oil Rents vs. Government Revenues); implied line/bar charts for GDP growth, sectoral contributions, trade, FDI, inflation trends.
## Key Findings
* Government Revenues remain stable despite fluctuations in Oil Rents, indicating limited direct dependence.
* GDP growth varies significantly (e.g., -0.55% in 1972 to 9.15% in 1975), reflecting economic volatility.
* Sectoral contributions show Services as a major contributor (~43–44%), followed by Agriculture (~34–35%) and Industry (~25–26%).
## How to Run This Project:
1. Clone the repository using `git clone https://github.com/your-username/GDP_Analysis.git`