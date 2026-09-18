# 🤖 AI Student Impact Analysis Project


## 📊 Data Analysis & Machine Learning Project
Analyzing how **Generative AI usage impacts student performance, dependency, and burnout risk**

---

# 📌 Project Overview

This project focuses on analyzing the impact of **Artificial Intelligence (AI)** on students using data analysis techniques.  
The dataset contains student behavior, AI usage, academic performance, and burnout-related information.

### 🎯 Main Objectives
✔ Analyze student AI usage patterns  
✔ Understand relationship between AI dependency and burnout  
✔ Study effect of AI usage on GPA  
✔ Perform data cleaning and exploratory data analysis (EDA)

---

# 🛠 Technologies Used

- 🐍 Python
- 📊 Pandas
- 🔢 NumPy
- 📈 Matplotlib
- 🎨 Seaborn
- 🗄 SQLite
- 📋 YData Profiling
- 📓 Jupyter Notebook

---

# 📂 Project Structure

```bash
AI-Student-Impact-Analysis/
│
├── Analysis.ipynb
├── ai_student_impact_dataset.csv
├── iris.json
├── database.db
├── ai_student_profile_report.html
└── README.md
```

---

# 🧠 Part A — Fundamentals

## 📌 What is Data Analysis?
Data Analysis is the process of collecting, cleaning, organizing, and examining data to extract useful insights and support better decision-making.

### Steps of Data Analysis
- Data Collection
- Data Cleaning
- Data Transformation
- Data Visualization
- Interpretation

---

## 📌 Data Science Project Lifecycle

1. Problem Definition  
2. Data Collection  
3. Data Cleaning  
4. Exploratory Data Analysis  
5. Feature Engineering  
6. Model Selection  
7. Model Training  
8. Evaluation  
9. Deployment  
10. Monitoring  

---

## 📌 Machine Learning Problem Statement

### Customer Churn Prediction
Predict whether a customer will stay or leave based on behavior and purchase history.

---

## 📌 Tensor Basics

### Types of Tensors
- 🔹 Scalar (0D)
- 🔹 Vector (1D)
- 🔹 Matrix (2D)
- 🔹 Higher Dimension Tensor (3D+)

Tensors are widely used in **Machine Learning** and **Deep Learning**.

---

# 📥 Part B — Data Acquisition

Data was collected using multiple sources:

### CSV File
- AI Student Impact Dataset

### JSON File
- Iris Dataset

### SQL Database
- Student Records

### API
- JSONPlaceholder API

---

# 🧹 Part C — Data Understanding & Cleaning

## Initial Exploration
Performed:
- `head()`
- `info()`
- `describe()`
- Missing value check
- Duplicate check

## Data Cleaning Steps
✔ Removed missing values  
✔ Converted data types  
✔ Removed unnecessary columns  

Example:
- Removed `Student_ID`
- Converted `Tool_Diversity` to integer

---

# 📊 Part D — Exploratory Data Analysis (EDA)

---

## 1️⃣ Univariate Analysis

### Histogram — Weekly GenAI Usage
Shows how many hours students spend using AI weekly.

### Burnout Risk Distribution
Shows count of:
- Low Risk
- Medium Risk
- High Risk

---

## 2️⃣ Bivariate Analysis

### AI Usage vs GPA
Scatter plot used to analyze relationship between:
- Weekly AI usage
- Post Semester GPA

### AI Dependency vs Burnout
Count plot used to compare:
- Dependency level
- Burnout risk

---

## 3️⃣ Multivariate Analysis

### Correlation Heatmap
Used to identify relationships between numerical features.

Helps detect:
- Positive correlations
- Negative correlations
- Strong dependencies

---

# 📋 Part E — Data Profiling

Used **YData Profiling** to generate automatic profiling report.

The report includes:

✔ Missing values  
✔ Descriptive statistics  
✔ Correlation analysis  
✔ Duplicate detection  
✔ Data quality warnings  

Generated File:
```bash
ai_student_profile_report.html
```

---

# 🔍 Key Insights

✅ Most students use AI for moderate hours weekly  
✅ Higher AI dependency may increase burnout risk  
✅ GPA and AI usage show observable patterns  
✅ Dataset has useful correlations for ML tasks  

---

# 🚀 Future Scope

- Build predictive ML models
- Burnout risk prediction
- Student performance forecasting
- AI dependency classification

---

# 📌 Conclusion

This project successfully demonstrates how **Data Analysis** can be used to understand the influence of **AI on students**.  
Using EDA and profiling, we discovered important patterns related to:

- Academic performance 📚  
- AI dependency 🤖  
- Burnout risk 😵‍💫  

---

## 🌟 Thank You
