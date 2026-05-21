# Providing Data-Driven Suggestions for HR

## Project Overview

This project analyzes employee attrition data to identify the major factors influencing employee turnover and provide actionable HR recommendations using machine learning and data analytics.

The analysis combines exploratory data analysis (EDA), feature engineering, statistical insights, and predictive modeling to help HR stakeholders better understand employee satisfaction, workload, tenure, and retention risks.

The project was completed using Python and machine learning models including Logistic Regression, Decision Trees, and Random Forest.

---

# Business Problem

Employee turnover can significantly affect organizational productivity, operational continuity, and recruitment costs. The goal of this project is to:

* Identify the main drivers of employee attrition
* Predict whether employees are likely to leave the company
* Provide data-driven recommendations for improving retention
* Support HR decision-making using predictive analytics

---

# Dataset Information

The dataset contains **14,999 employee records** with features related to:

* Employee satisfaction
* Performance evaluation
* Number of projects
* Monthly working hours
* Tenure
* Promotions
* Work accidents
* Department
* Salary level

### Key Variables

| Variable              | Description                        |
| --------------------- | ---------------------------------- |
| satisfaction_level    | Employee satisfaction score        |
| last_evaluation       | Last performance evaluation score  |
| number_project        | Number of projects handled         |
| average_monthly_hours | Average monthly working hours      |
| tenure                | Number of years spent at company   |
| work_accident         | Whether employee had work accident |
| promotion_last_5years | Promotion status                   |
| department            | Employee department                |
| salary                | Salary category                    |
| left                  | Employee attrition target variable |

---

# Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

# Project Workflow

## 1. Data Cleaning & Preparation

* Renamed columns into snake_case format
* Corrected misspelled variables
* Checked for missing values
* Reviewed data types and descriptive statistics
* Removed redundant features

## 2. Exploratory Data Analysis (EDA)

Performed analysis to identify:

* Attrition trends
* Workload patterns
* Employee satisfaction levels
* Department-level differences
* Relationships between evaluation scores and attrition

## 3. Feature Engineering

Created new variables including:

* `overworked`
* Employee tenure groupings
* Encoded categorical variables

## 4. Machine Learning Models

Built and evaluated multiple classification models:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

Hyperparameter tuning was performed using `GridSearchCV`.

---

# Model Performance

## Logistic Regression

* Accuracy: 83%
* Precision: 80%
* Recall: 83%
* F1 Score: 80%

## Decision Tree

* AUC: 93.8%
* Precision: 87.0%
* Recall: 90.4%
* F1 Score: 88.7%
* Accuracy: 96.2%

## Random Forest

The Random Forest model slightly outperformed the Decision Tree model and achieved the best overall predictive performance.

---

# Key Findings

The analysis revealed that employee attrition is strongly associated with:

* Excessive workload
* Long working hours
* High project counts
* Tenure-related dissatisfaction
* Lack of promotion opportunities

The most important predictive features were:

1. Last evaluation score
2. Number of projects
3. Tenure
4. Overworked status

---

# Business Recommendations

Based on the analysis, the following recommendations were proposed:

* Reduce excessive employee workload
* Limit the number of simultaneous projects
* Improve work-life balance policies
* Increase promotion opportunities for long-tenured employees
* Clarify overtime and compensation policies
* Improve employee engagement and workplace culture
* Reevaluate performance expectations tied to excessive work hours

---

# Visualizations Included

This project includes:

* Correlation analysis
* Employee attrition visualizations
* Feature importance charts
* Decision tree visualizations
* Confusion matrix analysis
* Distribution plots

---

# Repository Structure

```text
providing-data-driven-suggestions-for-hr/
│
├── data/
├── notebooks/
├── visuals/
├── README.md
├── requirements.txt
└── hr_attrition_analysis.ipynb
```

---

# How to Run the Project

## Clone Repository

```bash
git clone https://github.com/enowkelvin/providing-data-driven-suggestions-for-hr.git
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Notebook

```bash
jupyter notebook
```

---

# Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
jupyter
```

---

# Project Outcome

This project demonstrates practical skills in:

* Data cleaning
* Exploratory data analysis
* Feature engineering
* Machine learning
* Model evaluation
* HR analytics
* Business insight generation
* Data storytelling

---

# Author

## Enow Kelvin

Aspiring Data Analyst with experience in:

* Python
* SQL
* R
* Machine Learning
* Data Visualization
* Business Analytics

GitHub Portfolio:
[https://github.com/enowkelvin](https://github.com/enowkelvin)
