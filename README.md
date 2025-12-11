# tobacco-use-mortality-analysis
This repository contains an end-to-end data science project analyzing the relationship between tobacco use, smoking prevalence, economic indicators, hospital admissions, and smoking-related mortality.

📘 Tobacco Use & Mortality – Data Analysis & Prediction
Author: Archana Anil Mayacharya
Tools: Python, Pandas, NumPy, Seaborn, Scikit-learn, XGBoost, LightGBM
Goal: Analyze the impact of tobacco use on health outcomes and predict tobacco-related mortality using machine learning.
📌 Project Overview

This project integrates five public health datasets—including admissions, fatalities, smoking prevalence, prescriptions, and tobacco economics—to understand:

How tobacco use affects health outcomes

Which factors contribute most to mortality

How to predict high-risk cases using ML models

The workflow includes:

Data Cleaning

Data Integration

Feature Engineering

Exploratory Data Analysis (EDA)

Predictive Modeling

Insights & Recommendations

📊 Datasets Used

Hospital Admissions (ICD-10 diseases linked to smoking)

Smoking-Related Fatalities

Smoking Prevalence Survey Data

Tobacco Economic Metrics (price index, affordability, expenditure)

Smoking Cessation Prescriptions

All datasets were cleaned and merged into a consolidated analytical dataset.

🧹 Key Steps
1. Data Cleaning

Standardized column names

Converted year formats

Handled missing values (median/mode)

Converted numeric fields

Removed duplicates

2. Data Integration

Combined admissions & fatalities

Combined smokers & prescriptions

Merged all datasets on year and sex

3. Feature Engineering

Smoking prevalence (long format)

Duration of tobacco use

Lag features (previous-year prevalence & price index)

Interaction features

Disease indicators (cancer / circulatory / respiratory)

Normalized admissions

Log-transformed economic metrics

4. Exploratory Data Analysis

Distribution plots

Correlation heatmap

Smoking trends

Age-group heatmaps

Smoking vs. admissions relationships

🤖 Predictive Modeling

Models tested:

Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

XGBoost

LightGBM

SVM

Neural Network (MLP)

Best Performing Models (ROC-AUC):

Model	ROC-AUC
XGBoost	0.997
LightGBM	0.996
Random Forest	0.97
Gradient Boosting	0.95
🧠 Key Insights

Age and long-term exposure are major risk factors.

Tobacco expenditure intensity correlates with higher hospital admissions.

Ensemble models outperform traditional ML models.

Tobacco-related mortality is highly predictable using engineered features.
