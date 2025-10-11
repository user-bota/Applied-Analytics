### College Graduation Rate Analysis

This lab investigates how factors such as enrollment size, out-of-state tuition, student-faculty ratio, and instructional expenditure influence college graduation rates. Using Python, multiple linear regression models were fitted to identify the most significant predictors and compare model performance.

**Key Insight:**  
- Out-of-state tuition showed a strong positive relationship with graduation rate (R² ≈ 0.33).  
- Enrollment alone was not significant, but when combined with tuition, it became a weakly positive predictor.  
- Student-faculty ratio and instructional expenditure were not significant when controlling for other variables.  
- A log transformation of enrollment slightly improved model fit and corrected heteroscedasticity.  
- Simpler models using only Outstate and Enroll performed nearly as well as the full model, supporting interpretability and parsimony.

**How to Run:**  
1. Open the notebook in **Google Colab**.  
2. Run all cells to reproduce descriptive statistics, VIF analysis, regression models, and visual diagnostics.  

**Files Included:**  
- `Lab3.ipynb` — Google Colab notebook with all Python code and regression outputs.  
- `STAT_223_Lab3.pdf` — Detailed written report including statistical results, confidence/prediction intervals, and interpretation.

**Tools:** Python, pandas, NumPy, matplotlib, seaborn, statsmodels, scikit-learn.

