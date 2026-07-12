# Health Insurance Data Analysis

This project focuses on performing **Exploratory Data Analysis (EDA)** on a Health Insurance dataset to understand the relationships between customer attributes and insurance charges. Along with data analysis, a **Decision Tree Regressor** was implemented to predict insurance charges as a basic introduction to machine learning.

---

## Project Goal

The primary objective of this project is to analyze the Health Insurance dataset through data cleaning, visualization, statistical analysis, and feature exploration to extract meaningful insights. A Decision Tree Regression model is also built to understand the basic machine learning workflow and evaluate its prediction performance.

---

## Dataset Features

**Age • Sex • BMI • Children • Smoker • Region • Insurance Charges (Target)**

---

## Exploratory Data Analysis

**Data Inspection • Missing Value Analysis • Descriptive Statistics • Distribution Analysis • Outlier Detection • Correlation Analysis • Pair Plots • Hypothesis Testing • ANOVA • Feature Encoding**

---

## Machine Learning

A **Decision Tree Regressor** was trained to predict insurance charges.

### Workflow

Data Preprocessing → One-Hot Encoding → Train-Test Split → Decision Tree Regression → Model Evaluation → Hyperparameter Tuning (Bayesian Optimization)

> **Note:** The machine learning section is included to demonstrate the complete workflow of building and evaluating a regression model. Since the primary objective of this project is Exploratory Data Analysis, model comparison with other algorithms has not been included.

---

## Model Performance

* **Training R² Score:** 0.872
* **Testing R² Score:** 0.877

**Evaluation Metrics:** MAE • MSE • RMSE • R² Score

### Observations

* The Decision Tree model explained approximately **87%** of the variance in insurance charges.
* Training and testing R² scores are nearly identical, indicating good generalization.
* Bayesian Optimization was used to search for improved hyperparameters.
* The machine learning section complements the EDA and is included for learning purposes rather than model comparison.
