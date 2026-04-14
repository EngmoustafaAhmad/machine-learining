# Unsupervised Learning Algorithms

## Overview
Unsupervised Learning is a type of machine learning where:
- The model is trained on data **without labels**
- The goal is to **discover hidden patterns or structure** in the data

---

## Main Idea

In unsupervised learning:
- There is **no target variable (y)**
- The model tries to:
  - Group similar data points
  - Reduce dimensions
  - Find relationships

---

## Types of Unsupervised Learning Algorithms

### 1. Clustering Algorithms

Used to group similar data points into clusters.

#### Common Algorithms

- K-Means
  - Divides data into K clusters
  - Each point belongs to the nearest centroid

- Hierarchical Clustering
  - Builds a tree of clusters
  - Can be agglomerative (bottom-up) or divisive (top-down)

- DBSCAN (Density-Based Spatial Clustering)
  - Groups points based on density
  - Can detect noise and outliers

---

### 2. Dimensionality Reduction

Used to reduce the number of features while preserving important information.

#### Common Algorithms

- PCA (Principal Component Analysis)
  - Projects data into lower dimensions
  - Maximizes variance

- t-SNE (t-Distributed Stochastic Neighbor Embedding)
  - Used for visualization
  - Preserves local structure

- Autoencoders
  - Neural networks used for feature compression

---

### 3. Association Rule Learning

Used to find relationships between variables in large datasets.

#### Common Algorithms

- Apriori
  - Finds frequent itemsets
  - Used in market basket analysis

- Eclat
  - Similar to Apriori but more efficient in some cases

---

## Applications

- Customer segmentation
- Recommendation systems
- Anomaly detection
- Data compression
- Market basket analysis

---

## Summary

Unsupervised learning algorithms are used when:
- Data has no labels
- The goal is to explore structure and patterns

Main categories:
1. Clustering
2. Dimensionality Reduction
3. Association Rule Learning
