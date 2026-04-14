# Support Vector Machine (SVM)

## Overview
Support Vector Machine (SVM) is a supervised machine learning algorithm used for:
- Classification
- Regression (less common)

It aims to find the best boundary that separates data into different classes.

---

## What is SVM?

SVM finds a decision boundary called a **hyperplane** that separates classes.

The goal is to:
- Maximize the margin between classes
- Improve generalization

---

## Key Concepts 

### Hyperplane
A decision boundary:
- In 2D → a line
- In 3D → a plane
- In higher dimensions → a hyperplane

---

### Margin
The distance between the hyperplane and the nearest data points from each class.

- Larger margin → better model performance

---

### Support Vectors
The data points closest to the hyperplane.

- They determine the position of the boundary
- Removing them changes the model

---

## Objective of SVM

Maximize the margin between classes.

Mathematically, the hyperplane is defined as:

w^T x + b = 0


Margin boundaries:

w^T x + b = +1
w^T x + b = -1


Distance between margins:

2 / ||w||


SVM minimizes:

||w||

---

## Types of SVM

### Hard Margin SVM
- No misclassification allowed
- Works only if data is perfectly separable

---

### Soft Margin SVM
- Allows some misclassification
- More practical for real-world data

---

## Kernel Trick

When data is not linearly separable, SVM uses kernels to transform data into higher dimensions.

### Common Kernels
- Linear
- Polynomial
- Radial Basis Function (RBF)
- Sigmoid

Purpose:
- Make data linearly separable in higher-dimensional space

---

## Classification Rule

Final prediction:

y =
1 if w^T x + b >= 0
-1 otherwise


---

## Advantages

- Effective in high-dimensional spaces
- Works well with small datasets
- Robust to overfitting when margin is maximized

---

## Disadvantages

- Not suitable for very large datasets
- Choosing the right kernel can be difficult
- Sensitive to noise in some cases

---

## SVM vs Logistic Regression

| Feature | SVM | Logistic Regression |
|--------|-----|---------------------|
| Output | Class or margin | Probability |
| Objective | Maximize margin | Estimate probability |
| Kernel Trick | Yes | No |
| Dataset Size | Small to medium | Large datasets |

---

## Summary

Support Vector Machine is a supervised learning algorithm that finds the optimal hyperplane to separate classes by maximizing the margin between them. It uses support vectors and can handle non-linear data through kernel functions.

