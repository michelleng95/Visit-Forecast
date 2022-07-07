# Visit-Forecast
## Objective: To obtain an accurate forecast of future visits using historical data. 

## Sub-objectives: 
- Parse data and simplify data for ease of forecasting
- Determine which is more accurate for forecasting - ETS or ARIMA

## Steps: 
1. Import 'visits_data.yxdb'
2. Visualize raw data
3. Parse the dates and fill in null cells
4. Filter cleaned data, using first 8 years for forecasting and last year (2015) for validation
5. Using Join and TS Compare, determine which time series forecasting tool is more accurate -> ARIMA is more accurate in this case
6. Use ARIMA on the unfiltered dataset and perform TS Forecast
7. Obtained forecast of visits for the 12 months in 2016
