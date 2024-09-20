# Crime Data Analysis and Visualization

This repository contains a data analysis project that explores crime data from 2020 to 2023. Using **Pandas** for data manipulation and **Matplotlib** for visualizations, the project focuses on extracting insights from the dataset to better understand crime patterns over time.

## Project Overview

The project aims to analyze crime data by:
- Cleaning the dataset, removing irrelevant columns, and handling missing values.
- Converting date columns to the appropriate format for time-based analysis.
- Creating new features, such as year and month, to explore trends over time.
- Investigating the distribution of victim ages, victim demographics and reporting behaviors, crime trends over time, age 
  distributions, and top 20 crimes.
  
## Dataset

The analysis is based on the dataset: **`Crime Data.csv`**. Key columns include:
- `date_reported`, `date_occurred`, `victim_age`, `victim_sex`, `victim_descent`, `crime_code_description`, `area`, etc.

## Steps in the Analysis

1. **Data Loading and Exploration**
    - Imported data and explored basic information using Pandas functions like `.head()`, `.shape()`, and `.dtypes`.
  
2. **Data Cleaning**
    - Removed columns that were not necessary for the analysis using `.drop()`.
    - Checked for missing values with `.isna().sum()`.
  
3. **Datetime Formatting**
    - Converted `date_reported` and `date_occurred` columns to datetime format using `pd.to_datetime()`.
  
4. **Victim Age Analysis**
    - Filtered out invalid victim age values and analyzed the distribution of valid ages using `.value_counts()`.

5. **Feature Engineering**
    - Created new features such as year and month based on the `date_occurred` column for time-based analysis.


