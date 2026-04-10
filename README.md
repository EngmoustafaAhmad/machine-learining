# Machine Learning Learning Structure

This document provides a structured roadmap to learn Machine Learning, divided into Supervised Learning, Unsupervised Learning, and essential foundational topics.

---

# 1. Foundations

Before starting Machine Learning, you should learn:

## Programming
- Python basics
- Functions and loops
- File handling

## Libraries
- NumPy (arrays and numerical operations)
- Pandas (data analysis and manipulation)
- Matplotlib / Seaborn (data visualization)

## Basic Mathematics
- Mean, median, mode
- Standard deviation
- Probability basics
- Basic linear algebra concepts

---

# 2. Data Preprocessing

Data preprocessing is a critical step in Machine Learning.

## Steps
- Handle missing values
- Remove duplicates
- Encode categorical data:
  - Label Encoding
  - One-Hot Encoding
- Feature scaling:
  - StandardScaler
  - MinMaxScaler
- Split dataset into training and testing sets

---

# 3. Supervised Learning

## Definition
Supervised learning uses labeled data where the model learns the relationship between input (X) and output (Y).

---

## 3.1 Classification

### Definition
Predicts categorical outputs.

### Algorithms
- Logistic Regression
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

### Projects
- Spam Email Classification
- Disease Prediction
- Sentiment Analysis

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 3.2 Regression

### Definition
Predicts continuous numerical values.

### Algorithms
- Linear Regression
- Polynomial Regression
- Ridge Regression
- Lasso Regression
- Support Vector Regression (SVR)

### Projects
- House Price Prediction
- Salary Prediction
- Sales Forecasting

### Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## Workflow
Data → Preprocessing → Feature Engineering → Training → Testing → Evaluation

---

# 4. Unsupervised Learning

## Definition
Unsupervised learning works with unlabeled data and finds hidden patterns.

---

## 4.1 Clustering

### Algorithms
- K-Means Clustering
- DBSCAN
- Hierarchical Clustering

### Projects
- Customer Segmentation
- User Behavior Analysis

### Evaluation
- Silhouette Score

---

## 4.2 Dimensionality Reduction

### Algorithms
- Principal Component Analysis (PCA)
- t-SNE

### Use Cases
- Data visualization
- Feature reduction

---

## 4.3 Association Rules

### Algorithms
- Apriori
- Eclat

### Use Cases
- Market Basket Analysis

---

## Workflow
Data → Scaling → Pattern Discovery → Clustering or Reduction → Interpretation

---

# 5. Model Improvement

- Hyperparameter tuning
- Cross-validation
- Feature engineering
- Handling imbalanced datasets (SMOTE)

---

# 6. Advanced Topics

- Ensemble Learning (Bagging and Boosting)
- XGBoost / LightGBM
- Neural Networks
- Deep Learning basics
- Natural Language Processing (NLP)

---

# 7. Project Roadmap

## Beginner Projects
- Titanic Survival Prediction
- Spam Email Classification

## Intermediate Projects
- Movie Recommendation System
- Customer Segmentation

## Advanced Projects
- Chatbot using NLP
- Image Classification using CNN

---

# Final Learning Flow

Python → Data Preprocessing → Supervised Learning → Unsupervised Learning → Model Optimization → Projects → Deployment
