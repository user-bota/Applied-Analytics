### Democratic Vote Margin Analysis

This lab explores how socioeconomic and demographic variables such as unemployment rate, county type, PhD attainment, and average salary affect the Democratic vote margin across U.S. counties. Using Python, multiple linear regression models were built and refined through polynomial, log, and interaction transformations.

**Key Insight:**  
- Initial models revealed a strong negative linear relationship between unemployment and Democratic vote margin.  
- Adding a quadratic term for unemployment improved model fit (R² increased from 0.989 to 0.998).  
- A log transformation of PhD attainment further enhanced normality and linearity, producing an R² ≈ 1.000 with the lowest AIC (≈138).  
- Introducing interaction terms between county type and PhD showed that education effects vary by region, strongest in urban counties, weakest in rural ones.  
- The model achieved nearly perfect fit but with potential overfitting concerns, warranting caution in generalization.

**How to Run:**  
1. Open the notebook in **Google Colab**.  
2. Run all cells sequentially to reproduce the regression models, diagnostic plots, and model comparisons.

**Files Included:**  
- `Lab4.ipynb` — Google Colab notebook with all Python code and visualizations.  
- `STAT_223_Lab4.pdf` — Detailed report including statistical results, transformations, and interpretation.

**Tools:** Python, pandas, NumPy, matplotlib, seaborn, statsmodels, scikit-learn.
