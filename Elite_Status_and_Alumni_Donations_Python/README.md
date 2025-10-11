### Elite Status and Alumni Donations Analysis

This lab investigates factors influencing whether U.S. universities are classified as **elite** and what drives the **percentage of alumni who donate**. Using Python, both logistic and multiple linear regressions were performed to study institutional and academic predictors of prestige and engagement.

**Key Insight:**  
- **Elite Status (Logistic Regression):**  
  - The probability of being elite increases with higher faculty terminal degrees (`Terminal`) and instructional expenditure (`Expend`).  
  - Decision boundaries were found near 100.4 for `Terminal` and 18,294 for `Expend`, separating elite from non-elite institutions.  
- **Alumni Donations (Linear Regression):**  
  - `GradRate`, `Private`, and `Top10perc` were the strongest positive predictors of alumni giving.  
  - Adding `Terminal` improved explanatory power slightly (R² ≈ 0.349 → 0.386).  
  - The simplified model without `Expend` achieved nearly identical performance (R² ≈ 0.383), demonstrating parsimony without loss of accuracy.  
  - Private institutions averaged ~8–9% higher alumni giving than public ones, controlling for other factors.  

**How to Run:**  
1. Open the notebook in **Google Colab**.  
2. Run all cells sequentially to reproduce the logistic and linear regression models, plots, and tables.  

**Files Included:**  
- `Lab5.ipynb` — Google Colab notebook with all Python code and visualizations.  
- `STAT_223_Lab5.pdf` — Full written report including regression outputs, interpretations, and comparisons.

**Tools:** Python, pandas, NumPy, matplotlib, seaborn, statsmodels, scikit-learn.
