# 🩺 Healthcare Data Preprocessing Project

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange?style=for-the-badge&logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-red?style=for-the-badge&logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blueviolet?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-teal?style=for-the-badge)

</p>

---

# 📌 Project Overview

This project focuses on **Healthcare Data Preprocessing** using Python.

The main objective is to clean the dataset by handling missing values and outliers so that the data becomes accurate, consistent, and ready for further analysis or machine learning.

---

# 🎯 Project Objectives

- ✅ Load the healthcare dataset
- ✅ Explore the dataset
- ✅ Identify missing values
- ✅ Handle missing values using different techniques
- ✅ Detect outliers
- ✅ Remove or treat outliers
- ✅ Compare dataset before and after preprocessing

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-Learn | Missing Value Imputation |
| SciPy | Statistical Functions |

---

# 📂 Dataset Information

| Feature | Description |
|----------|-------------|
| Age | Patient Age |
| Gender | Male/Female |
| BMI | Body Mass Index |
| Blood Pressure | Blood Pressure |
| Glucose | Glucose Level |
| Cholesterol | Cholesterol Level |
| Region | Patient Region |

---

# 🔍 Missing Value Handling

Different techniques were used for different columns.

| Column | Method Used |
|----------|-------------|
| BMI | Mean Imputation |
| BMI (Comparison) | Median Imputation |
| Region | Most Frequent |
| Gender | Most Frequent |
| Cholesterol | Random Sample Imputation |
| Glucose | MICE (Iterative Imputer) |
| Age | KNN Imputer |

---

# 📊 Outlier Detection Methods

The following methods were applied.

| Column | Method |
|----------|---------|
| Cholesterol | Z-Score |
| Glucose | Z-Score |
| BMI | IQR |
| Glucose | Percentile Clipping |
| Blood Pressure | Winsorization |

---

# 📈 Visualizations

The project includes:

- 📦 Box Plot
- 📊 Statistical Summary
- 📋 Dataset Shape
- 📉 Outlier Detection
- 📌 Missing Value Analysis

---

# ⚙ Project Workflow

```text
Dataset
   │
   ▼
Load Dataset
   │
   ▼
Check Missing Values
   │
   ▼
Handle Missing Values
   │
   ▼
Detect Outliers
   │
   ▼
Treat Outliers
   │
   ▼
Compare Results
   │
   ▼
Clean Dataset Ready
```

---

# 📁 Project Structure

```
Healthcare_Preprocessing/
│
├── dataset.csv
├── preprocessing.ipynb
├── README.md
└── requirements.txt
```

---

# 📊 Results

✔ Missing values removed successfully

✔ Outliers detected and treated

✔ Dataset cleaned successfully

✔ Data ready for analysis and machine learning

---

# 🚀 Future Scope

- Data Visualization Dashboard
- Machine Learning Models
- Disease Prediction
- Feature Engineering
- Model Evaluation

---

# 📚 Libraries Used

```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
from scipy import stats
from scipy.stats.mstats import winsorize
from sklearn.impute import SimpleImputer
from sklearn.impute import KNNImputer
from sklearn.impute import IterativeImputer
```

---

# 👩‍💻 Author

**Vishva Movaliya**

BCA Student | Data Analytics Enthusiast

---

# ⭐ Thank You

If you found this project useful,

⭐ Star this repository

🍴 Fork this repository

📩 Feel free to connect

---

<p align="center">

### ❤️ Thank You for Visiting ❤️

</p>