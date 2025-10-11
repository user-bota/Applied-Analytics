### Association Rules and Decision Tree Classification

This lab explores two key machine learning techniques: **Association Rule Mining** and **Decision Tree Classification**. Using Python, it analyzes both transactional market basket data and baseball team performance data to demonstrate how patterns and predictive models are built from real-world datasets.

**Key Insight:**  
- **Association Rule Mining:**  
  - Support, confidence, and lift were computed for market basket transactions.  
  - The highest lift was found for the rule *(Pizza → Beer)*, suggesting a strong association between these items (Lift ≈ 1.07).  
  - Symmetry in lift and support demonstrated consistency across related itemsets.  
- **Decision Tree Classification:**  
  - A tree trained without depth limits achieved 80.1% accuracy.  
  - Limiting the maximum depth to 3 improved accuracy to 82.7%, showing that simpler models can generalize better by avoiding overfitting.  
  - Gini impurity and information gain metrics confirmed that the chosen splits improved class purity and predictive power.

**How to Run:**  
1. Open the notebook in **Google Colab**.  
2. Run all cells sequentially to reproduce the association rules, plots, and decision tree models.  
3. Optional: adjust `max_depth` or support/confidence thresholds to explore model sensitivity.

**Files Included:**  
- `Lab9.ipynb` — Google Colab notebook containing all code and outputs.  
- `STAT_223_Lab9.pdf` — Report summarizing association metrics, decision tree results, and key visuals.

**Tools:** Python, pandas, NumPy, matplotlib, seaborn, scikit-learn, mlxtend.
