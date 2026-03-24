# 📊 Islington Unemployment Analysis

This project analyses unemployment trends in the **London Borough of Islington** using real-world data from the iWork employment support programme (2018–2021).

The goal is to identify socio-demographic factors influencing employment outcomes and build a predictive model to classify employment status.

---

## 📌 Project Overview

This study explores:

- Demographic characteristics (age, gender, ethnicity)
- Socio-economic factors (education, benefits, disability)
- Employment outcomes

The project follows a full data analytics pipeline:
- Data cleaning and preprocessing
- Descriptive statistics
- Data transformation
- Correlation analysis
- Predictive modelling (Logistic Regression)

---

## 🧠 Key Findings

- Strong class imbalance between employed and unemployed
- Statistically significant predictors:
  - Year of registration
  - Disability status
  - Parent status
  - Education level
- Weak but significant correlation between age and employment
- Model achieved:
  - **ROC-AUC = 0.818 (81.8% accuracy)**

---

## 🛠 Tools & Technologies

- **SPSS**
- Statistical Analysis
- Logistic Regression
- ROC Curve Evaluation

---

## 🧹 Data Cleaning & Preparation

Key preprocessing steps included:

- Handling missing values (NULL → "Unknown")
- Removing variables with excessive missing data
- Encoding categorical variables
- Grouping age into categories
- Converting target variable:
  - "No Outcome" → "Unemployed"
  - Created binary classification (Employed vs Unemployed)

---

## 📊 Analysis Performed

### Descriptive Statistics
- Frequency distributions
- Bar charts for categorical variables
- Central tendency (mean, median, mode)

### Correlation Analysis
- Pearson correlation used
- Weak but statistically significant relationship between age and employment

### Predictive Modelling
- Logistic Regression model
- Addressed class imbalance using weighting
- Evaluated using ROC-AUC curve

---

## 📈 Results

- ROC-AUC Score: **0.818**
- Model shows strong ability to distinguish employment status
- Key drivers of employment identified

---

## 🎓 Academic Context

Module: **CC5063 – Data Analytics**  
Student: **Sam Griffiths**  
Year: **2024–2025**

---

## 📄 Licence

This project is for academic purposes only.
