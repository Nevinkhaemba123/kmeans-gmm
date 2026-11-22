# K-Means and Gaussian Mixture Models (GMM) Clustering Analysis

**Author:** Nevin Wanjala Khaemba  
**Date:** November 22, 2026  

## Overview
This repository explores and compares two fundamental unsupervised clustering algorithms—**K-Means Clustering** and **Gaussian Mixture Models (GMM)**—to uncover latent patterns and group structures within multidimensional data.

## Methodology
1. **Data Preprocessing & Exploration:**
   - Handled missing values, outliers, and feature distributions.
   - Applied feature scaling (`StandardScaler`) to prevent distance-based distortion during clustering.
2. **K-Means Clustering:**
   - Evaluated optimal cluster count ($k$) using the **Elbow Method** (Within-Cluster Sum of Squares / Inertia) and **Silhouette Score**.
   - Assigned hard cluster labels based on Euclidean distance to cluster centroids.
3. **Gaussian Mixture Models (GMM):**
   - Fitted probabilistic clusters using the Expectation-Maximization (EM) algorithm.
   - Selected optimal components using **Akaike Information Criterion (AIC)** and **Bayesian Information Criterion (BIC)**.
   - Generated soft cluster assignments (posterior probabilities) to capture overlapping or elliptical cluster structures.
4. **Model Comparison & Visualization:**
   - Compared hard vs. soft clustering boundaries, cluster cohesion, and separation.
   - Visualized cluster assignments and decision boundaries across key feature dimensions.

## Repository Structure
```text
kmeans-gmm/
├── README.md               # Project documentation
├── *.ipynb                 # Jupyter Notebook with K-Means & GMM implementation
└── data/                   # Dataset(s) used for clustering (if applicable)
