##  Pandas

**Pandas** is a powerful Python library used for data manipulation and analysis.  
It allows you to work with structured data like tables (similar to Excel or SQL).

---

###  What Pandas Does
- Works with tabular data (rows & columns)
- Handles missing or messy data
- Filters, transforms, and analyzes datasets
- Reads and writes files (CSV, Excel, etc.)

---

### Core Concept: DataFrame

```python
import pandas as pd

data = {
    "name": ["Ali", "Sara", "John"],
    "age": [20, 22, 25]
}

df = pd.DataFrame(data)
print(df)
```


### Read Data from File

```
df = pd.read_csv("data.csv")
```

### View Data

```
print(df.head())   # First 5 rows
print(df.tail())   # Last 5 rows
print(df.info())   # Data types
```

### Select Columns

 ```
print(df["name"])          # Single column
print(df[["name", "age"]]) # Multiple columns
```


### Filter Data
```
filtered = df[df["age"] > 21]
print(filtered)
➕ Add New Column
df["age_plus_5"] = df["age"] + 5
```

### Handle Missing Values
```
df.dropna()      # Remove missing values
df.fillna(0)     # Replace missing with 0
```


### Basic Statistics
```
print(df.describe())
🔄 Sort Data
df.sort_values("age", ascending=False)
```


## Use Cases
Data cleaning and preprocessing
Working with CSV/Excel files
Data analysis and reporting
Preparing data for Machine Learning

