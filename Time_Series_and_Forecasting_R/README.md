### Time Series and Forecasting in R

This lab applies multiple time series analysis techniques using R to explore trend, seasonality, transformation, and forecasting. The datasets include international arrivals to Australia, stock indices, mortality rates, and Olympic performance data. The lab demonstrates decomposition, Box-Cox transformations, autocorrelation analysis, and forecasting evaluation.

**Key Insight:**  
- **Arrivals Data:** Japan, New Zealand, UK, and US arrivals to Australia all showed upward trends with strong seasonal patterns. Japan and the UK peaked in summer, while New Zealand and the US had peak arrivals in winter and spring.  
- **Dow Jones Index:** Daily changes exhibited no significant autocorrelation, confirming white noise behavior.  
- **Transformations:** Box-Cox transformations applied to `dole`, `usdeaths`, and `bricksq` data showed minimal ACF improvement, suggesting raw data sufficed.  
- **Beer Production Forecasting:** Seasonal naïve models captured seasonality well, though residuals showed mild autocorrelation at lag 4.  
- **IBM Stock Forecasting:** Among mean, naïve, seasonal naïve, and drift forecasts, the drift method performed best, capturing downward trends accurately.  
- **Men’s 400m Olympic Data:** A linear trend regression (R² ≈ 0.823) effectively modeled the decrease in winning times, predicting the 2020 Olympic time (43.85s) with near-perfect accuracy.

**How to Run:**  
1. Open the `STAT 223 Lab 6.R` script in **RStudio**.  
2. Load the provided time series datasets (e.g., arrivals, usdeaths, beer, IBM, mens400).  
3. Run all code chunks to generate seasonal plots, ACFs, and forecasts.

**Files Included:**  
- `STAT 223 Lab 6.R` — R script with all time series analysis steps and visualizations.  
- `STAT_223_Lab6.pdf` — Full written report with plots, interpretations, and results.

**Tools:** R, RStudio, forecast, ggplot2, fpp3, dplyr.
