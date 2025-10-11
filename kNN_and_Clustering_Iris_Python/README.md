### kNN and Clustering on Iris

This lab applies k-Nearest Neighbors (kNN) for classification and explores unsupervised clustering with K-Means and Hierarchical Clustering (single, complete, group-average linkages) on the Iris dataset.

**Key Insight:**  
- **Best k for kNN:** `k = 21` balanced bias/variance with ~0.80 test accuracy and closely matched training accuracy, indicating limited overfitting.  
- **K-Means (k=3):** Cleanly separates the Setosa cluster; some overlap remains between Versicolor and Virginica due to feature similarity.  
- **Hierarchical Clustering:**  
  - *Single link* forms chain-like clusters and is sensitive to outliers.  
  - *Complete link* yields compact, well-separated clusters.  
  - *Group average* sits between single and complete, offering balanced shapes.  
These results are supported by the accuracy table and clustering plots in the report. :contentReference[oaicite:0]{index=0}

**How to Run:**  
1. Open `Lab8.ipynb` in **Google Colab**.  
2. Run all cells to reproduce kNN selection, K-Means clustering, and hierarchical dendrograms.  
3. Optionally adjust `k`, distance metrics, or linkage methods to compare outcomes.

**Files Included:**  
- `Lab8.ipynb` — Google Colab notebook with all Python code and visuals.  
- `STAT_223_Lab8.pdf` — Written report summarizing accuracy, cluster separation, and linkage behavior.

**Tools:** Python, pandas, NumPy, matplotlib, seaborn, scikit-learn, SciPy.
