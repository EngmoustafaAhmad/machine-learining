## 📌 NumPy

**NumPy** is a core Python library for numerical computing.  
It allows you to work with arrays, matrices, and perform fast mathematical operations efficiently.

---

### 🧠 What NumPy Does
- Handles arrays (1D, 2D, multi-dimensional)
- Supports matrix operations
- Performs fast mathematical computations
- Provides statistical and linear algebra functions

---

### 🔢 Create Arrays & Matrices

```python
import numpy as np

# 1D Array
arr = np.array([1, 2, 3, 4])

# 2D Array (Matrix)
matrix = np.array([
    [1, 2],
    [3, 4]
])

print(arr)
print(matrix)
```


### Fast Mathematical Operations

```
arr = np.array([1, 2, 3, 4])

print(arr * 2)     # Multiply all elements
print(arr + 5)     # Add to all elements
print(arr ** 2)    # Square each element
```


### Statistical Functions

```
arr = np.array([1, 2, 3, 4, 5])

print(np.mean(arr))   # Average
print(np.sum(arr))    # Sum
print(np.max(arr))    # Max value
print(np.min(arr))    # Min value
```

### Reshaping Arrays

```
arr = np.array([1, 2, 3, 4, 5, 6])

reshaped = arr.reshape(2, 3)
print(reshaped)
```

### Indexing & Slicing

```
matrix = np.array([
    [10, 20, 30],
    [40, 50, 60]
])

print(matrix[0, 1])   # 20
print(matrix[:, 1])   # Column: [20 50]
```

### Broadcasting

```
arr = np.array([1, 2, 3])

print(arr + 10)   # [11 12 13]

```

### Matrix Operations

```
a = np.array([[1, 2], [3, 4]])
b = np.array([[5, 6], [7, 8]])

print(np.dot(a, b))  # Matrix multiplication
```

## Use Cases
Machine Learning (data preparation)
Image processing (pixels as arrays)
Scientific computing
Data analysis



