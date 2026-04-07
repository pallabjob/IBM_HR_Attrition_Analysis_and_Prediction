# 📊 HR Attrition Analysis & Prediction (End-to-End Project)

## 🔍 Project Overview

This project analyzes employee data to identify factors affecting attrition and builds a machine learning model to predict whether an employee is likely to leave the company.

---

## 🎯 Objectives

* Analyze employee attrition trends
* Identify key factors influencing attrition
* Build a predictive model using Machine Learning
* Provide actionable business insights

---

## 🧹 Data Cleaning

* Removed irrelevant columns (EmployeeCount, StandardHours, Over18)
* Checked for missing values and duplicates
* Converted target variable (Attrition: Yes → 1, No → 0)
* Applied One-Hot Encoding using pandas

---

## 📊 Exploratory Data Analysis (EDA)

* Attrition distribution analysis
* Attrition by Department, Job Role, Gender
* Overtime impact on attrition
* Salary vs Attrition analysis
* Correlation heatmap

---

## 🤖 Machine Learning Model

* Models Used:

  * Logistic Regression
  * Random Forest Classifier
* Data preprocessing:

  * Train-test split
  * Feature scaling
* Evaluation Metrics:

  * Accuracy
  * Confusion Matrix
  * Classification Report

---

## 📈 Key Insights

* Employees working overtime are more likely to leave
* Low job satisfaction increases attrition risk
* Employees with fewer years at company leave more
* Salary has moderate impact on attrition

---

## 🚀 Results

* Random Forest achieved better performance than Logistic Regression
* Identified top features influencing attrition using feature importance

---

## 🛠️ Tech Stack

* Python (Pandas, NumPy)
* Data Visualization (Matplotlib, Seaborn)
* Machine Learning (Scikit-learn)

---

## 📌 Future Improvements

* Hyperparameter tuning (GridSearchCV)
* Use advanced models like XGBoost
* Deploy using Streamlit

Pallab Kanti Lahiri
