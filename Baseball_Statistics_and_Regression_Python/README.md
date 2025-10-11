### Baseball Statistics and Regression Analysis

This lab applies Python to analyze Major League Baseball performance metrics and relationships between key variables such as batting average (BA), home runs (HR), slugging percentage (SLG), and winning percentage (WinPct). It includes function design, visualization, and regression modeling to understand performance trends.

**Key Insight:**  
- A custom `MADfun()` function was written to compute the Mean Absolute Difference (MAD) with data validation.  
- Standardized batting average (BAStd) analysis showed a symmetric distribution with minor outliers.  
- Regression between **Weighted Runs Created (wRC)** and **WinPct** demonstrated a strong positive relationship (R² = 0.447).  
- Relationships between **Home Runs Allowed (HRA)** and **Strikeouts (SO)**, and between **ERA** and **OPS**, showed smaller but statistically significant correlations.  
- Residual and Q–Q plots confirmed good model fit and approximate normality of residuals.

**How to Run:**  
1. Open the notebook in **Google Colab**.  
2. Run all cells sequentially to reproduce the descriptive analysis, scatterplots, and regression outputs.

**Files Included:**  
- `Lab2.ipynb` — Google Colab notebook containing all Python code and visualizations.  
- `STAT_223_Lab2.pdf` — full written report summarizing regression models, diagnostics, and interpretations.

**Tools:** Python, pandas, NumPy, matplotlib, seaborn, statsmodels.
