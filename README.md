# Student-Performance-Analysis-EDA
# 📊 Student Performance Analysis — EDA

## Thirenix Project 3

An Exploratory Data Analysis (EDA) project focused on analyzing
student academic performance and identifying patterns, trends,
and relationships between different factors.

---

## 📌 Project Overview

This project analyzes student performance data using Python and
exploratory data analysis techniques.

The analysis explores academic, demographic, social, and
school-related factors and their relationship with students'
final mathematics grade.

The project was developed as part of **Student-Performance-Analysis-EDA**.

---

## 🎯 Objectives

- Understand the structure of the student performance dataset
- Perform data quality and statistical analysis
- Analyze the distribution of student grades
- Identify correlations between different variables
- Study factors associated with final academic performance
- Create meaningful data visualizations
- Extract useful insights from the dataset

---

## 📂 Dataset

The dataset used in this project is the **Student Performance
Dataset** from the UCI Machine Learning Repository.

The dataset contains information related to:

- Student demographics
- Academic performance
- Study habits
- Family background
- Social activities
- School support
- Absences
- Previous failures
- Final grades

The main target variable used for analysis is:

**G3 — Final Grade**

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Analysis Performed

### 1. Dataset Overview

- Number of records
- Number of features
- Data types
- Dataset structure

### 2. Data Quality Analysis

- Missing value detection
- Duplicate record detection
- Data type inspection

### 3. Statistical Analysis

- Mean
- Median
- Standard deviation
- Minimum and maximum values
- Quartiles

### 4. Exploratory Data Analysis

The project analyzes relationships between:

- Study time and final grade
- Previous failures and final grade
- Absences and final grade
- Gender and final grade
- Internet access and final grade
- School support and final grade
- Paid extra classes and final grade
- Extracurricular activities and final grade
- Higher education plans and final grade

### 5. Correlation Analysis

A correlation matrix and heatmap were used to identify
relationships between numerical variables.

---

## 📊 Key Findings

- **G2** showed the strongest positive correlation with final grade
  (**0.905**).
- **G1** also showed a strong positive correlation with final grade
  (**0.801**).
- Previous failures showed a moderate negative correlation with
  final grade (**-0.360**).
- Study time showed only a weak positive correlation with final
  grade (**0.098**).
- Absences showed almost no linear correlation with final grade
  (**0.034**).
- Students with internet access had a higher average final grade
  in this dataset.
- Parental education showed weak positive relationships with
  academic performance.

> **Note:** Correlation indicates association and does not prove
> causation.

---

## 📈 Visualizations

The project includes:

- Final grade distribution
- Grade comparison boxplot
- Study time vs final grade
- Previous failures vs final grade
- Absences vs final grade
- Gender vs final grade
- Correlation heatmap
- G1 vs G3 scatter plot
- G2 vs G3 scatter plot
- Categorical factor comparisons
- Student performance categories

---

## 📁 Project Structure

```text
Thirenix-Project-3-EDA/
│
├── Student_Performance_EDA.ipynb
├── student-mat.csv
└── README.md
