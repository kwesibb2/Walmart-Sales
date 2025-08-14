# Walmart Sales Forecasting by State

## Overview
This project predicts weekly Walmart sales across California, Texas, and Wisconsin. Using OLS, Lasso regression, and time series models (AR, MA, ARMA), we evaluated predictive accuracy and selected ARMA models for each state based on RMSE performance.

## Key Insights & Business Relevance

### State-Specific Shopping Patterns
- California and Wisconsin required higher-lag ARMA models, reflecting more concentrated sales in fewer stores.
- Texas required fewer lags, consistent with higher store density and more frequent customer purchases.  
**Business takeaway:** Inventory and staffing can be tailored to state-specific shopping behaviors to reduce stockouts and overstock.

### Sales Drivers Identified
- Lasso regression highlighted key predictors including holidays, price, weekday, and SNAP availability.  
**Business takeaway:** Companies can optimize promotions and pricing strategies using these insights to potentially increase sales.

### Seasonality Patterns
- Weekday-level trends showed predictable weekend peaks and Monday dips.  
**Business takeaway:** Enables better workforce scheduling and delivery planning, aligning resources with expected demand cycles.

## Technical Skills Demonstrated
- Time series modeling (AR, MA, ARMA) and cross-validation for Lasso regression.
- RMSE-based model evaluation and comparison.
- Data wrangling and preprocessing for multiple states.

## Individual Contribution
- ARMA modeling for California, Texas, and Wisconsin.
- RMSE calculation and visualization of predicted vs. actual sales.
- Analysis of models and deriving actionable business insights.

## Impact Potential
While actual cost or revenue impact was not quantified, the modeling approach provides a foundation for operational improvements, such as reducing excess inventory, optimizing staffing, and informing promotion strategy based on forecasted demand.

## Files
- `scripts/` : R scripts for modeling and analysis
- `data/` : Example dataset or cleaned data
- `figures/` : Visualizations including RMSE bar charts

## Bibliography
1. Crown, M. (2016). Weekly sales forecasts using non-seasonal ARIMA models. http://mxcrown.com/walmart-sales-forecasting/
2. Jeswani, R. (2011). Predicting Walmart Sales, Exploratory Data Analysis, and Walmart Sales Dashboard. www.rit.edu/ischoolprojects/node/104009.
3. Levy, D., Chen, H., Müller, G., Dutta, S., & Bergen, M. (2010). Holiday Price Rigidity and Cost of Price Adjustment. Economica, 77: 172-198. https://doi.org/10.1111/j.1468-0335.2008.00738.x
4. Statista (2023). Number of Walmart Stores in the United States as of 2023, by State. https://www.statista.com/statistics/1167169/walmart-number-of-stores-by-state-us/
