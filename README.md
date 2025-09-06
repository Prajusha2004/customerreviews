# 🛒 Customer Reviews Clustering for Market Research

This project clusters customer reviews into meaningful groups using **unsupervised machine learning**.  
It helps businesses uncover hidden insights such as customer preferences, product issues, and emerging themes from large sets of reviews.

## 🚀 Features
- Preprocessing customer reviews with **TF-IDF vectorization**
- Applying **K-Means, DBSCAN, and Hierarchical Clustering**
- Selecting the **best clustering algorithm** based on silhouette scores
- Extracting **keywords for each cluster** to understand group themes
- Visualizing clusters in **2D using PCA**
- Exporting results to **`final_clustered_results.csv`**

## 📂 Workflow
1. **Data Preparation** – Clean and preprocess customer reviews.
2. **Vectorization** – Convert reviews into numerical vectors using `TfidfVectorizer`.
3. **Clustering** – Apply K-Means, DBSCAN, and Hierarchical algorithms.
4. **Evaluation** – Compute silhouette scores to measure cluster quality.
5. **Comparison** – Select the best clustering algorithm.
6. **Keyword Extraction** – Identify top keywords per cluster.
7. **Visualization** – Plot results with PCA for interpretability.
8. **Export Results** – Save final labeled data to CSV.

## 📊 Example Output
- Best Algorithm: **K-Means**  
- Number of Clusters: **5**  
- Keywords per cluster:
  - Cluster 0: galaxy, samsung, note, work, card  
  - Cluster 1: great, work, price, card, use  
  - ...

## ⚙️ Requirements
- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
