<div align="center">

# Lab 3: Exploratory Data Analysis (EDA)

**Applying EDA Techniques to the Heart Disease Dataset**

[![Dataset](https://img.shields.io/badge/Dataset-UCI%20Heart%20Disease-red?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJ3aGl0ZSI+PHBhdGggZD0iTTEyIDIxLjM1bC0xLjQ1LTEuMzJDNS40IDE1LjM2IDIgMTIuMjggMiA4LjUgMiA1LjQyIDQuNDIgMyA3LjUgM2MxLjc0IDAgMy40MS44MSA0LjUgMi4wOUMxMy4wOSAzLjgxIDE0Ljc2IDMgMTYuNSAzIDE5LjU4IDMgMjIgNS40MiAyMiA4LjVjMCAzLjc4LTMuNCA2Ljg2LTguNTUgMTEuNTRMMTIgMjEuMzV6Ii8+PC9zdmc+)](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
[![Problem](https://img.shields.io/badge/Problem-Binary%20Classification-blue)](#)
[![Samples](https://img.shields.io/badge/Samples-297-green)](#)
[![Features](https://img.shields.io/badge/Features-13-orange)](#)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](#)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](#)
[![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)](#)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Plotting-11557C)](#)

</div>

---

## Overview

> In this lab, we apply **Exploratory Data Analysis (EDA)** techniques to the UCI Heart Disease dataset to understand the data before building any machine learning model.

EDA is the first and most important step in any ML project. Before building models, we must understand what the data represents, identify missing values and outliers, discover patterns, and determine which variables influence others.

| | Detail |
|---|--------|
| **Lab Topic** | Exploratory Data Analysis (EDA) |
| **Dataset** | UCI Heart Disease |
| **Problem Type** | Binary Classification |
| **Target** | `target` -- 0 (No Disease) / 1 (Disease) |
| **Samples** | 297 patients |
| **Features** | 13 medical attributes |

---

## EDA Techniques Applied

| # | Technique | Description |
|:-:|-----------|-------------|
| 1 | Missing Values Check | Identify null/missing entries using `isna()` |
| 2 | Duplicate Detection | Find repeated rows using `duplicated()` |
| 3 | Shape Inspection | Check number of rows and columns |
| 4 | Data Type Analysis | Review column types and convert where needed |
| 5 | Descriptive Statistics | Summary statistics with `describe()` |
| 6 | Univariate Analysis | Distribution histograms for age, cholesterol, max heart rate |
| 7 | Bivariate Analysis | Disease rate by sex, chest pain type; cholesterol by target; scatter plots |
| 8 | Correlation Matrix | Heatmap of feature correlations |
| 9 | Feature Analysis | Ranking features by correlation with target variable |

---

## Dataset Features

| # | Feature | Description | Type |
|:-:|---------|-------------|:----:|
| 1 | `age` | Age in years | Numeric |
| 2 | `sex` | 1 = Male, 0 = Female | Binary |
| 3 | `cp` | Chest pain type (1-4) | Categorical |
| 4 | `trestbps` | Resting blood pressure (mm Hg) | Numeric |
| 5 | `chol` | Serum cholesterol (mg/dl) | Numeric |
| 6 | `fbs` | Fasting blood sugar > 120 mg/dl | Binary |
| 7 | `restecg` | Resting ECG results (0-2) | Categorical |
| 8 | `thalach` | Maximum heart rate achieved | Numeric |
| 9 | `exang` | Exercise-induced angina (1 = yes) | Binary |
| 10 | `oldpeak` | ST depression induced by exercise | Numeric |
| 11 | `slope` | Slope of peak exercise ST segment | Categorical |
| 12 | `ca` | Major vessels colored by fluoroscopy | Numeric |
| 13 | `thal` | Thalassemia (3 = normal, 6 = fixed, 7 = reversible) | Categorical |

---

## Key Findings

| Finding | Detail |
|---------|--------|
| Missing Values | 0 across all columns |
| Duplicates | None detected |
| Class Balance | 160 healthy vs 137 disease (relatively balanced) |
| Age Range | 29 to 77 years, most patients between 50-65 |
| Top Positive Correlations | `cp`, `thalach` positively correlated with heart disease |
| Top Negative Correlations | `exang`, `oldpeak`, `ca` negatively correlated with heart disease |

---

## Files

```
Lab3/
├── heart.csv       # UCI Heart Disease dataset
├── Lab3.ipynb      # Jupyter Notebook -- full EDA analysis
└── README.md       # This file
```
