# Salary Prediction using Simple Linear Regression

A machine learning project demonstrating end-to-end regression modeling to predict employee salaries based on years of experience. This project covers data ingestion, preprocessing, exploratory data analysis (EDA), model building, and evaluation.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Machine Learning Pipeline](#machine-learning-pipeline)
- [Dataset Overview](#dataset-overview)
- [Project Architecture](#project-architecture)
- [Installation & Requirements](#installation--requirements)
- [Usage](#usage)
- [Model Evaluation & Results](#model-evaluation--results)

---

## Project Overview

This repository provides an implementation of a Simple Linear Regression model to analyze the relationship between professional experience (`YearsExperience`) and salary (`Salary`).

### Key Highlights:
- **Task Type:** Supervised Learning (Regression)
- **Primary Features:** `YearsExperience`
- **Target Variable:** `Salary`
- **Exploratory Data Analysis:** Data cleaning, missing value checks, duplicate handling, and scatter plot visualizations.

---

## Machine Learning Pipeline

1. **Data Collection:** Load raw salary dataset from CSV.
2. **Data Preparation & Cleaning:** 
   - Detect and handle duplicate records.
   - Inspect and handle missing/null values.
   - Remove redundant index/unnamed columns.
3. **Exploratory Data Analysis (EDA):** Visualize feature-target relationships using `matplotlib`.
4. **Dataset Splitting:** Partition dataset into training and test sets.
5. **Model Building:** Select and fit a Simple Linear Regression algorithm.
6. **Model Testing & Evaluation:** Benchmark predictions against ground truth metrics.

---

## Dataset Overview

The dataset contains employee salary records mapped to their total years of professional experience.

### Dataset Features:
| Feature Name | Data Type | Description |
| :--- | :--- | :--- |
| **`YearsExperience`** | Float | Number of years of professional work experience |
| **`Salary`** | Float | Annual salary associated with the experience |

### Summary Statistics:
- **Total Samples:** 30
- **Missing Values:** 0
- **Duplicate Rows:** 0

---

## Project Architecture
