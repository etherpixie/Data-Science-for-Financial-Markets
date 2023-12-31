# Data-Science-for-Financial-Markets
Short projects for timeseries data analysis and financial market analytics.

## Cross-Correlation Analysis and Lag Optimisation for two crypto assets
This Python code performs cross-correlation analysis between the closing prices of Bitcoin (BTC) and Ethereum (ETH) over time. 
 - It retrieves the historical price data for both assets from Yahoo Finance using Pandas data reader.
 - The data is aligned based on common dates. Cross-correlation is then calculated by shifting one of the time series and measuring the correlation at different lags.
 - The lag with maximum correlation indicates the temporal offset between the movements of the two assets.
 - Plots are generated to visualize the normalized time series with the optimal lag applied.
This analysis helps identify correlations and potential lead-lag effects between the prices of Bitcoin and Ethereum cryptocurrencies.
