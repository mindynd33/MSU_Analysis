# Medicare Saturation and Utilization Analysis

## Objective
Current Instacart sales are on target, but execs would like to uncover additional information about sales patterns. The task is to perform an initial data and exploratory analysis of some of their data to derive insights and suggest better strategies for improved segmentation.

## Key Questions
1. Which states have the highest/lowest utilization rates?
2. Is there a relationship between number of users and number of providers?
3. Which types of services were paid the most?
4. Is there a relationship between the number of providers and type of service?

## Data
This data set comprises of the following: 
- Medicare part A & B fee for service claims by:
- county
- state
- number of providers
- number of users
- number of fee for service beneficiaries
- some pre-aggregated variables

Open source data from data.cms.gove was used and can be obtained from [here]([https://www.instacart.com/datasets/grocery-shopping-2017](https://data.cms.gov/summary-statistics-on-use-and-payments/program-integrity-market-saturation-by-type-of-service/market-saturation-utilization-core-based-statistical-areas])

## Tools
- pandas and numpy for data analysis
- seaborn and matplotlib for visualizations
- folium for spatial analysis
- scikit-learn for regression analysis

## Executing the code
The code is available as jupyter notebooks, which are available under /03 Scripts

## Misc
Visualizations are available under /04 Analysis/.

Final report is available in [Tableau] ([https://public.tableau.com/app/profile/mindy.dong/viz/MedicareUtilizationMarketSaturationAnalysisV1_16854256965220/MarketSaturationandUtilization#1]) 
