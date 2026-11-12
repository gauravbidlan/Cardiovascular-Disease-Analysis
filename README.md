# 🫀 Cardiovascular Disease Analysis (End-to-End Data Analytics Project)

## 📌 Overview

This project focuses on analyzing cardiovascular disease using a dataset containing approximately **70,000 patient records**, with 11 independent features and 1 target variable.

The objective is to explore patient demographics, clinical indicators, and lifestyle factors to identify patterns and understand their association with cardiovascular disease.

---

## 🎯 Objective

To investigate the relationship between demographic, medical, and lifestyle factors and cardiovascular disease through structured data analysis and visualization.

Key objectives include:

- Understanding cardiovascular disease distribution across patients.
- Identifying important demographic and clinical indicators.
- Analyzing the relationship between lifestyle habits and disease prevalence.
- Exploring patterns in blood pressure, cholesterol, glucose, and BMI.
- Extracting meaningful insights through exploratory data analysis.

---

## 📂 Dataset Description

- **Source:** Kaggle – Cardiovascular Disease Dataset
- **Total Records:** 70,000
- **Independent Features:** 11
- **Target Variable:** Cardio
- **Problem Type:** Binary Classification

### Dataset Features

| Feature | Description |
|---|---|
| Age | Patient age (days) |
| Gender | Patient gender |
| Height | Height (cm) |
| Weight | Weight (kg) |
| Ap_hi | Systolic blood pressure |
| Ap_lo | Diastolic blood pressure |
| Cholesterol | Cholesterol level |
| Gluc | Glucose level |
| Smoke | Smoking status |
| Alco | Alcohol consumption |
| Active | Physical activity status |
| Cardio | Cardiovascular disease (Target) |

---

## 🔄 Project Workflow

### 📥 1. Data Collection
- Downloaded the cardiovascular disease dataset from Kaggle.
- Imported the dataset for analysis.

### 📊 2. Data Understanding
- Examined dataset dimensions and structure.
- Identified numerical and categorical variables.
- Analyzed feature distributions and target variable.

### 🧹 3. Data Cleaning & Preprocessing
- Checked for missing values and duplicate records.
- Identified inconsistent and invalid observations.
- Examined outliers in clinical measurements.
- Prepared the dataset for exploratory analysis.

### 🐍 4. Exploratory Data Analysis (EDA)
- Analyzed demographic characteristics.
- Investigated clinical indicators.
- Explored lifestyle-related patterns.
- Examined relationships between independent variables and cardiovascular disease.
- Created visualizations to communicate findings.

### 📈 5. Insights & Recommendations
- Identified important patterns within patient records.
- Evaluated the relationship between clinical indicators and disease prevalence.
- Developed data-driven observations and recommendations.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Project Structure

```text
Cardiovascular-Disease-Analysis/
│
├── 1_Data/
│   └── cardio_train.csv
│
├── 2_Data_Preprocessing/
│   └── cleaned_cardio_data.csv
│
├── 3_Exploratory_Data_Analysis/
│   └── cardiovascular_analysis.ipynb
│
├── 4_Documentation/
│   └── README.md
│
└── README.md
```

---

## 📌 Conclusion

This project explores cardiovascular disease data through a structured analytical approach, focusing on demographic, clinical, and lifestyle-related variables.

It demonstrates the application of data analytics techniques to healthcare data and the process of converting raw patient records into meaningful insights.

---

## ⚠️ Disclaimer

This project is intended for educational and analytical purposes only. The findings should not be interpreted as medical advice or used for clinical diagnosis.
