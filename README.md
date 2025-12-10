# 📊 Promotion Readiness Analysis – EDA Project
## A Data-Driven HR Analytics Case Study | GlobeHR

This project analyzes a large-scale HR dataset from a multinational organization (GlobeHR) operating across 28 regions with over 15,000 employees. The objective is to explore promotion patterns, identify key performance drivers, uncover potential biases, and prepare the dataset for machine learning.

This repository contains a full end-to-end Exploratory Data Analysis (EDA) pipeline, data cleaning workflows, visualizations, insights, and an ML-ready dataset.

## 🔍 Project Overview

Every year, GlobeHR conducts an internal promotion cycle. Leadership raised several concerns:

Only ~8% of employees were promoted.

Many high-performing employees may be overlooked.

Promotion decisions appear inconsistent across regions.

Biases related to gender, education, or region may exist.

The process is manual, slow, and lacks data-backed insights.

This project addresses these concerns using Python-based EDA and statistical analysis.

## 🎯 Objectives

Clean and prepare the dataset for analysis and modeling

Identify key drivers of employee promotion

Detect potential biases in gender, education, or region

Explore overlooked high-potential employees

Prepare a machine-learning-ready dataset

Provide actionable insights for HR policy improvement

## 🧹 Task 1 — Data Cleaning & Preparation

Includes:

Assessment using .info(), .describe(), unique values

Handling missing values (gender, education, department, ratings)

Fixing spelling errors (e.g., “Markting” → “Marketing”)

Standardizing labels

Removing duplicates

Converting categorical and numerical types

Final clean dataframe ready for EDA

## 📈 Task 2 — Univariate Analysis

Analyzed individual variables:

Age

Gender

Department

Region

Training score

Previous performance rating

KPI achievement

Visualizations include:

Histograms

Countplots

Boxplots

Distribution curves

## 🔗 Task 3 — Bivariate Analysis With Promotion

Explored how each feature relates to is_promoted:

Promotion rate by gender

Promotion rate by department

Ratings vs promotion

Training score vs promotion

KPI > 80% effect

Awards influence

Visualizations:

Grouped bar charts

Boxplots (promoted vs not-promoted)

Side-by-side KDE distributions

## 🔀 Task 4 — Multivariate Analysis

Correlation heatmap

Pairplot (key numerical variables)

Interaction insights:

Employees with high rating + high training score are most likely to be promoted

KPI achievement amplifies promotion probability

## 📝 Task 5 — Business Insights Summary

A complete insights brief including:

Top 3 predictors of promotion

Overlooked talent groups

Policy improvement areas

Biases requiring investigation

Strategic, actionable recommendations

This is written in a professional, corporate format suitable for reporting to HR leadership.

## 🤖 Task 6 — Machine Learning Preparation (Optional)

One-hot encoding of categorical variables

Standard scaling of numerical features

Final ML-ready feature matrix (X) and target (y)

Ready for models such as Logistic Regression, Random Forest, and XGBoost

## 🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

## 📊 Key Findings (Short Summary)

KPI achievement, previous performance rating, and training scores are the strongest predictors of promotion.

Several high-potential employees are overlooked, especially in large departments.

Promotion rates vary significantly across regions and departments.

Award distribution disproportionately affects promotion outcomes.

HR should adopt a data-driven, standardized promotion framework.

## 🙌 About This Project

This project demonstrates practical data science skills in:

Data cleaning

Exploratory analysis

Feature engineering

Visualization

Insight generation

Machine learning preparation

Professional reporting

It reflects real-world HR analytics problem-solving in a corporate environment.
