# Titanic Dataset Cleaning Project

## Project Overview

This project demonstrates data cleaning using Python and Pandas on the Titanic dataset.

The dataset was checked for missing values, duplicate records, data types, and categorical values.

## Dataset

The Titanic dataset was obtained from the public Seaborn dataset repository.

## Tools Used

- Python
- Pandas
- Google Colab
- GitHub

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

Categorical columns were checked for inconsistent values. No inconsistent categorical labels were found in the inspected data.

## Final Result

After cleaning:

- Missing values: 0
- Duplicate records: 0

The cleaned dataset is available as:

`cleaned_titanic.csv`

## Files

- `original_titanic.csv` - Original dataset
- `cleaned_titanic.csv` - Cleaned dataset
- `README.md` - Project documentation3##
