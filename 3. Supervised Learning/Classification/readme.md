# Supervised Learning - Classification

## Overview
Supervised Learning is a type of machine learning where:
- The model is trained using **labeled data**
- Each input has a corresponding **output label**

Classification is a task in supervised learning where:
- The goal is to **predict a discrete class label**

---

## What is Classification?

Classification is the process of:
- Assigning input data to one of several predefined categories

### Examples
- Email → Spam or Not Spam
- Image → Cat or Dog
- Disease detection → Positive or Negative

---

## Types of Classification

### 1. Binary Classification
- Two classes only
- Examples:
  - 0 or 1
  - Yes or No

---

### 2. Multiclass Classification
- More than two classes
- Example:
  - Classifying animals: Cat, Dog, Bird

---

### 3. Multi-label Classification
- One sample can belong to multiple classes
- Example:
  - Image contains both "cat" and "dog"

---

## Common Classification Algorithms

### 1. Logistic Regression
- Outputs probability
- Uses sigmoid function
- Good for binary classification

---

### 2. Support Vector Machine (SVM)
- Finds the best boundary (hyperplane)
- Maximizes margin between classes

---

### 3. K-Nearest Neighbors (KNN)
- Classifies based on nearest neighbors
- Simple and intuitive

---

### 4. Decision Tree
- Uses tree structure
- Splits data based on feature values

---

### 5. Random Forest
- Ensemble of decision trees
- Improves accuracy and reduces overfitting

---

### 6. Naive Bayes
- Based on probability (Bayes theorem)
- Assumes feature independence

---

## Classification Workflow

1. Collect labeled data
2. Split data into training and testing sets
3. Train the model
4. Make predictions
5. Evaluate performance

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Applications

- Spam detection
- Image classification
- Medical diagnosis
- Fraud detection
- Sentiment analysis

---

## Summary

Classification is a supervised learning task that predicts discrete labels.

Key points:
- Uses labeled data
- Output is categorical
- Many algorithms can be used depending on the problem
