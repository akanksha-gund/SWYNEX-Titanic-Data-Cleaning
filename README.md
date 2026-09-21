# Titanic Dataset Cleaning & Exploratory Data Analysis Project

## Project Overview

This project demonstrates data cleaning and exploratory data analysis (EDA) using Python and Pandas on the Titanic dataset.

The project is divided into two tasks:

- Task 1 – Data Cleaning
- Task 2 – Exploratory Data Analysis (EDA)

## Dataset

The Titanic dataset was obtained from the public Seaborn dataset repository.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

# Task 1 – Data Cleaning

## Data Quality Checks

The dataset was checked for:

- Missing values
- Duplicate records
- Data types
- Categorical values

## Data Cleaning Performed

### 1. Missing Values

- Missing `age` values were replaced using the median.
- Missing `embarked` values were replaced using the mode.
- Missing `embark_town` values were replaced using the mode.
- Missing `deck` values were replaced with `Unknown`.

### 2. Duplicate Records

Duplicate records were identified and removed using Pandas.

### 3. Data Types

Categorical columns were converted from `object` to `category` data type.

### 4. Categorical Values

Categorical columns were checked for inconsistent values.

## Final Result

After cleaning:

- Missing values: 0
- Duplicate records: 0

# Task 2 – Exploratory Data Analysis (EDA)

This task focuses on Exploratory Data Analysis of the Titanic dataset using Python.

## Analysis Performed

- Survival analysis
- Gender and passenger class analysis
- Age and fare analysis
- Embarkation analysis
- Family-size analysis
- Correlation analysis
- Outlier analysis
- Data visualization
- Key insights and conclusions

## Task 2 Notebook

The complete EDA analysis is available in:

`Titanic_EDA_Task2.ipynb`

## Files

- `original_titanic.csv` - Original Titanic dataset
- `cleaned_titanic.csv` - Cleaned Titanic dataset
- `Titanic_EDA_Task2.ipynb` - Exploratory Data Analysis notebook
- `README.md` - Project documentation
