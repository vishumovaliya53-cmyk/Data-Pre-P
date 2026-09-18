# 💳 Customer Credit Risk Data Preprocessing

<p align="center">

<img src="https://img.shields.io/badge/Project-Customer%20Credit%20Risk-blue?style=for-the-badge">

<img src="https://img.shields.io/badge/Python-3.12-yellow?style=for-the-badge&logo=python">

<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-orange?style=for-the-badge&logo=pandas">

<img src="https://img.shields.io/badge/Scikit--Learn-Preprocessing-green?style=for-the-badge&logo=scikit-learn">

<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">

</p>

<p align="center">

### 📊 Complete Data Cleaning & Preprocessing Project

**Turning Raw Customer Data into Clean, Meaningful & ML-Ready Data 🚀**

</p>

---

## 🔗 Quick Navigation

<p align="center">

[📌 About](#-about-the-project) •
[🎯 Objectives](#-project-objectives) •
[📂 Dataset](#-dataset-information) •
[🔍 Workflow](#-project-workflow) •
[🧹 Cleaning](#-data-cleaning) •
[📊 Transformation](#-data-transformation) •
[🎥 Video](#-project-video) •
[🤖 ML Ready](#-machine-learning-readiness)

</p>

---

# 📌 About the Project

The **Customer Credit Risk Data Preprocessing Project** focuses on preparing customer credit data for analysis and Machine Learning.

The dataset contains information about customers, income, loans, credit scores, repayment history and other financial details.

The main purpose of this project is to identify and handle data quality problems before using the dataset for Machine Learning.

---

# 🎯 Project Objectives

| # | Objective | Purpose |
|---|---|---|
| 01 | 📥 Data Acquisition | Collect data from different sources |
| 02 | 🔍 Data Understanding | Understand structure and quality |
| 03 | 🧹 Data Cleaning | Remove data quality problems |
| 04 | ❌ Missing Value Handling | Handle missing information |
| 05 | 🚨 Outlier Detection | Identify unusual values |
| 06 | 🔢 Encoding | Convert categorical data |
| 07 | ⚖️ Scaling | Bring numerical features to similar scale |
| 08 | 🔄 Transformation | Improve data distribution |
| 09 | 🛠️ Feature Construction | Create useful new features |
| 10 | 🤖 ML Preparation | Prepare final dataset for ML |

---

# 📊 Dataset Information

### 📦 Dataset Name

**Customer Credit Risk Dataset**

### 📈 Dataset Type

**Structured Tabular Data**

### 🎯 Target Variable

**`default_flag`**

| Value | Meaning |
|---|---|
| 🟢 0 | No Default |
| 🔴 1 | Default |

---

# 🗂️ Dataset Columns

| Column | Description |
|---|---|
| 🆔 `customer_id` | Unique customer identifier |
| 🎂 `age` | Customer age |
| 👤 `gender` | Customer gender |
| 🌍 `region` | Customer region |
| 🎓 `education_level` | Education level |
| 💼 `employment_type` | Employment type |
| 💰 `annual_income` | Annual income |
| 🏦 `loan_amount` | Requested loan amount |
| 🎯 `loan_purpose` | Purpose of loan |
| ⭐ `credit_score` | Credit score |
| 💳 `repayment_history` | Missed payments |
| 🔄 `transaction_count` | Number of transactions |
| 💸 `spending_ratio` | Spending-to-income ratio |
| 📅 `join_date` | Customer joining date |
| ⚠️ `default_flag` | Loan default indicator |

---

# 🔄 Project Workflow

```text
📥 Data Acquisition
        ↓
🔍 Data Understanding
        ↓
🧹 Data Cleaning
        ↓
❌ Missing Value Handling
        ↓
🚨 Outlier Detection
        ↓
🔢 Encoding
        ↓
⚖️ Feature Scaling
        ↓
🔄 Transformation
        ↓
🛠️ Feature Construction
        ↓
🎯 Binning & Binarization
        ↓
🧩 Column Transformer
        ↓
✅ Final ML-Ready Dataset
```

---

# 📥 Data Acquisition

The project demonstrates data acquisition from multiple sources.

| Source | Data |
|---|---|
| 📄 CSV | Main customer credit dataset |
| 🧾 JSON | Customer metadata |
| 🗄️ SQL | Loan repayment history |
| 🌐 API | External economic indicators |

---

# 🔍 Data Understanding

Data understanding is performed to understand the structure and quality of the dataset.

### 🔎 Main Checks

- 📋 Dataset structure
- 🔢 Data types
- ❌ Missing values
- 📊 Statistical summary
- 🔁 Duplicate records
- 📈 Data distribution

### 💡 Interpretation

Data understanding helps us identify the structure and problems in the dataset before preprocessing.

---

# 📊 Data Profiling

A profiling report is created to get an overall view of the dataset.

### 🔎 Profiling Includes

- 📌 Variable information
- ❌ Missing values
- 🔢 Unique values
- 📊 Distributions
- 🔗 Correlations
- 🔁 Duplicate records
- ⚠️ Data quality warnings

### 📄 Report

`Customer_Credit_Risk_Profile.html`

---

# 🧹 Data Cleaning

Data cleaning is performed to improve the quality of the dataset.

### Main Cleaning Tasks

| Task | Method |
|---|---|
| ❌ Missing Values | Imputation |
| 🚨 Outliers | Detection & Treatment |
| 🔁 Duplicates | Identification |
| 🏷️ Categories | Encoding |
| 📅 Dates | Date Feature Extraction |
| 📏 Numerical Values | Scaling & Transformation |

---

# ❌ Missing Value Handling

Different methods are used according to the type of data.

| Method | Purpose |
|---|---|
| 📊 Mean Imputation | Fill missing numerical values using mean |
| 📊 Median Imputation | Fill missing values using median |
| 🏷️ Most Frequent | Fill missing categorical values |
| 🔎 KNN Imputer | Estimate missing values using nearby records |
| 🔄 MICE | Iterative missing value estimation |
| 🗑️ Complete Case Analysis | Remove incomplete records |
| 🚩 Missing Indicator | Identify missing information |

### 💡 Interpretation

Different techniques help handle missing data while keeping useful information in the dataset.

---

# 🚨 Outlier Detection

An outlier is an unusual value that is very different from other observations.

### Methods Used

| Method | Purpose |
|---|---|
| 📊 Z-Score | Detect extreme values |
| 📦 IQR | Detect values outside the normal range |
| 📈 Percentile | Identify extreme values |
| ✂️ Winsorization | Reduce the effect of extreme values |

### Important Features

- 💰 Annual Income
- 🏦 Loan Amount
- ⭐ Credit Score

### 💡 Interpretation

Outlier treatment reduces the effect of extreme values and can make the dataset more suitable for Machine Learning.

---

# 🔢 Encoding

Encoding converts categorical data into numerical form.

| Encoding Method | Example |
|---|---|
| 🔢 Ordinal Encoding | `education_level` |
| 🏷️ Label Encoding | Simple categorical variables |
| 🎯 One-Hot Encoding | `gender`, `region`, `loan_purpose` |

### 💡 Interpretation

Encoding converts categorical information into numbers so that Machine Learning algorithms can process it.

---

# ⚖️ Feature Scaling

Feature scaling brings numerical features to a similar scale.

| Scaling Method | Purpose |
|---|---|
| 📏 Standardization | Scale values using mean and standard deviation |
| 📐 Normalization | Scale values to a common range |
| 📊 Min-Max Scaling | Convert values to a fixed range |
| ➕ MaxAbs Scaling | Scale using maximum absolute value |
| 🛡️ Robust Scaling | Reduce the effect of outliers |

### 💡 Interpretation

Scaling prevents features with large numerical values from dominating smaller-valued features.

---

# 🔄 Data Transformation

Transformation techniques can be applied to improve the distribution of numerical features.

### Techniques

- 📈 Log Transformation
- 🔄 Reciprocal Transformation
- √ Square Root Transformation
- 📦 Box-Cox Transformation
- 🔄 Yeo-Johnson Transformation

### 💡 Interpretation

Transformation can reduce skewness and make numerical data more suitable for analysis and Machine Learning.

---

# 🛠️ Feature Construction

Feature construction creates new useful features from existing data.

### 💰 Debt-to-Income Ratio

Shows the relationship between loan amount and annual income.

### 💸 Spending-to-Income Ratio

Helps understand customer spending compared with income.

### 📅 Date Features

The joining date can be used to create:

- 📆 Year
- 📅 Month
- 🗓️ Weekday

### 💡 Interpretation

New features can provide additional useful information for analysis and Machine Learning.

---

# 🎯 Binarization

Binarization converts numerical values into two categories.

### Example

| Credit Score | Category |
|---|---|
| ⭐ Greater than 700 | 🟢 High |
| ⭐ 700 or below | 🔴 Normal |

### 💡 Interpretation

Binarization converts continuous numerical information into simple categories.

---

# 📦 Binning & Discretization

Binning divides continuous numerical values into groups.

### Example

| Income Range | Category |
|---|---|
| 💰 Low | Low Income |
| 💰💰 Medium | Medium Income |
| 💰💰💰 High | High Income |

### Methods

- 📊 Quantile Binning
- 🤖 K-Means Binning

### 💡 Interpretation

Binning makes continuous numerical data easier to understand and categorize.

---

# 🧩 Column Transformer

Column Transformer allows different preprocessing methods to be applied to different columns.

| Column Type | Processing |
|---|---|
| 🔢 Numerical | Scaling |
| 🏷️ Categorical | Encoding |
| 📅 Date | Feature Extraction |

### 💡 Interpretation

Column Transformer combines multiple preprocessing steps into one organized workflow.

---

# 🤖 Machine Learning Readiness

After preprocessing, the dataset becomes ready for Machine Learning.

### 🚀 Final Pipeline

```text
Raw Customer Data
       ↓
Data Understanding
       ↓
Missing Value Handling
       ↓
Outlier Treatment
       ↓
Encoding
       ↓
Scaling
       ↓
Transformation
       ↓
Feature Construction
       ↓
Binning & Binarization
       ↓
Clean Dataset
       ↓
🤖 Machine Learning
```

---

# 🎥 Project Video

<p align="center">

## ▶️ Watch the Complete Project Video

<a href="https://drive.google.com/file/d/14054KwvaXNfkyATxvpu1sFmpSilb00bf/view?usp=drive_link">

<img src="https://img.shields.io/badge/▶️%20Watch%20Project%20Video-Google%20Drive-red?style=for-the-badge">

</a>

</p>

### 🎬 Video Link

👉 [**Click Here to Watch Project Video**](https://drive.google.com/file/d/14054KwvaXNfkyATxvpu1sFmpSilb00bf/view?usp=drive_link)

---

# 📁 Project Files

| File | Description |
|---|---|
| 📊 `Customer_Credit_Risk_Dataset.csv` | Original dataset |
| 📊 `Final_Cleaned_Customer_Credit_Risk.csv` | Final cleaned dataset |
| 📑 `Customer_Credit_Risk_Profile.html` | Data profiling report |
| 🧾 `customer_metadata.json` | Customer metadata |
| 🗄️ `loan_database.db` | SQLite database |
| 📓 `analysis.ipynb` | Complete project notebook |
| 📘 `Theory.pdf` | Theory and definitions |
| 🎥 `Project Video` | Complete project explanation |
| 📖 `README.md` | Project documentation |

---

# 📈 Project Highlights

| Area | Work Completed |
|---|---|
| 📥 Data Acquisition | ✅ |
| 🔍 Data Understanding | ✅ |
| 📊 Data Profiling | ✅ |
| 🧹 Data Cleaning | ✅ |
| ❌ Missing Value Handling | ✅ |
| 🚨 Outlier Detection | ✅ |
| 🔢 Encoding | ✅ |
| ⚖️ Feature Scaling | ✅ |
| 🔄 Transformation | ✅ |
| 🛠️ Feature Construction | ✅ |
| 🎯 Binarization | ✅ |
| 📦 Binning | ✅ |
| 🧩 Column Transformer | ✅ |
| 🤖 ML Preparation | ✅ |

---

# ✅ Final Outcome

This project demonstrates a complete **Customer Credit Risk Data Preprocessing Workflow**.

### The project covers:

**📥 Data Acquisition → 🔍 Data Understanding → 🧹 Data Cleaning → ❌ Missing Values → 🚨 Outliers → 🔢 Encoding → ⚖️ Scaling → 🔄 Transformation → 🛠️ Feature Construction → 🎯 Binarization → 📦 Binning → 🧩 Column Transformer → 🤖 ML Ready Dataset**

---

<p align="center">

# 🚀 Raw Data → Clean Data → ML Ready Data

### 💳 Customer Credit Risk Data Preprocessing

**Made with 🐍 Python • 🐼 Pandas • 📊 Scikit-Learn**

</p>

---

<p align="center">

⭐ **Thank you for visiting this project!** ⭐

</p>