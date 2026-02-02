# SpatialEconometrics_IDF

## Project Overview
This project analyzes the determinants of rent per square meter at the municipal level in the Île-de-France region, explicitly accounting for spatial interactions between municipalities.

## Methodology
The analysis follows three main steps:

1. **Data Preparation**
   - Socio-economic data sourced from *Observatoire des Territoires*.  
   - Spatial boundaries sourced from *cadastre.data.gouv.fr*.  
   - Final sample: 1,250 municipalities.

2. **Descriptive and Spatial Analysis**
   - Exploratory data analysis (statistics, distributions, correlations).  
   - Visualization using maps to highlight spatial disparities in rents, income, and population density.

3. **Spatial Econometric Modeling**
   - Ordinary Least Squares (OLS) model as a benchmark.  
   - Moran’s I test to detect spatial autocorrelation.  
   - Lagrange Multiplier (LM) tests to identify spatial dependence type.  
   - Spatial Durbin Model (SDM) estimation to capture direct and indirect effects of explanatory variables.  
   - Model selection validated using Akaike Information Criterion (AIC) and Likelihood Ratio tests.

## Key Results
- Strong spatial dependence in rents (ρ ≈ 0.75).  
- Income, population density, and sports facilities have significant direct and spillover effects.  
- Commercial density shows a negative indirect effect.  
- Unemployment rate and share of foreign residents have minimal impact after controlling for other variables.

## Data
- **Socio-economic variables:** income, population density, unemployment, share of foreigners, sports facilities, local shops.  
- **Spatial variables:** municipal boundaries (geometry).  
- All data are available in the `data/` folder (sensitive data anonymized if needed).

## Contributors
- **REN Yue:** Data cleaning, descriptive analysis, visualizations.  
- **Khadija Mahamadou Issoufou :** Data cleaning , Econometric modeling, interpretation of results.

