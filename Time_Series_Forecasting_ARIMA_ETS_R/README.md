### Time Series Forecasting with ARIMA and ETS Models

This lab applies advanced time series modeling techniques in R to analyze and forecast real-world data, including plastics sales, livestock counts, book sales, commodity prices, and macroeconomic indicators. It compares ARIMA and ETS models, explores stationarity, and evaluates model accuracy using AIC and RMSE metrics.

**Key Insight:**  
- **Plastics:** Clear upward trend and strong seasonality; decomposition showed stable residuals and a well-defined seasonal pattern.  
- **Pigs & Books:** Simple Exponential Smoothing (SES) produced stable forecasts, while Holt’s method captured upward trends more effectively, lowering RMSE for both paperback and hardcover sales.  
- **Eggs:** Comparing Holt variants revealed that the Box-Cox transformation achieved the lowest RMSE (≈26.39), improving forecast accuracy.  
- **IBM Stock Prices:** ACF/PACF confirmed non-stationarity; transformations and differencing were necessary for model stability.  
- **US Electricity & GDP:** Box-Cox and differencing steps successfully removed trend; ARIMA(2,1,0) yielded the best fit (AIC ≈ −115) for GDP, outperforming ETS.  
- **Copper Prices:** **ARIMA(0,1,1)** outperformed ETS (AIC −86 vs. 8052), confirming its superior residual behavior and forecast reliability.

**How to Run:**  
1. Open the `STAT 223 Lab 1+7.R` script in **RStudio**.  
2. Load the relevant time series datasets (e.g., plastics, pigs, books, eggs, ibmclose, usgdp, mcopper).  
3. Run all sections to generate decompositions, Box-Cox transformations, ARIMA/ETS models, and residual diagnostics.

**Files Included:**  
- `STAT 223 Lab 1+7.R` — R script with full analysis, model fitting, and visualizations.  
- `STAT_223_Lab7.pdf` — Written report with plots, RMSE/AIC tables, and interpretation.

**Tools:** R, RStudio, forecast, fpp3, ggplot2, dplyr.
