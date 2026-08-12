# AI-Powered Dataset Quality Analysis for Machine Learning Pipelines

An AI-integrated system that automatically analyzes datasets used in Machine Learning pipelines, identifies data-quality issues, calculates an overall quality score, and provides intelligent recommendations for improving the dataset before model training.

---

## 📌 Project Overview

Data quality plays an important role in the performance and reliability of Machine Learning models.

Manually checking datasets for missing values, duplicate records, incorrect data types, outliers, and class imbalance can be time-consuming.

This project automates the dataset-quality analysis process using data-processing techniques and AI-based recommendations.

The system allows users to upload a dataset and receive a detailed analysis of its quality along with actionable recommendations.

---

## 🎯 Objectives

- Automatically analyze uploaded datasets.
- Detect common data-quality problems.
- Identify missing and duplicate records.
- Detect potential outliers.
- Identify incorrect or inconsistent data types.
- Analyze class imbalance in classification datasets.
- Generate an overall dataset-quality score.
- Use AI to explain detected problems.
- Provide recommendations for improving dataset quality.
- Help prepare datasets before Machine Learning model training.

---

## ✨ Features

### Dataset Upload
- Upload CSV datasets.
- Validate uploaded files.
- Display basic dataset information.

### Data Quality Analysis
The system analyzes:

- Missing values
- Duplicate records
- Data types
- Unique values
- Constant/low-variance columns
- Numerical outliers
- Class imbalance
- Basic statistical information

### Quality Score

The system generates an overall quality score based on the detected data-quality issues.

Example:

```text
Dataset Quality Score: 82 / 100

Status: Good

Issues Found:
- 3.2% missing values
- 47 duplicate records
- 2 columns with potential outliers
- Moderate class imbalance
