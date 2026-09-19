# Data Cleaning & Feature Engineering — 

## Project Goal

The goal of this project is to practice data cleaning and feature engineering using Pandas by working with a real-world Data Science jobs dataset.

The project focuses on identifying and handling missing/invalid values, removing duplicates, transforming inconsistent data formats, and creating meaningful features from existing columns.


## Dataset Source

The original dataset was obtained from **Kaggle**:

https://www.kaggle.com/datasets/rashikrahmanpritom/data-science-job-posting-on-glassdoor/data

This is a **real world dataset scrapped from Glassdoor's website**, containing only job posts for the role Data Science. 
The dataset was used for practicing data cleaning and feature engineering. The original raw dataset is not included in this repository; the repository contains the cleaned dataset and the notebook documenting the transformation process.


## Dataset

The dataset contains job postings with information such as:

- Job Title
- Salary Estimate
- Job Description
- Rating
- Company
- Location
- Company Size
- Founded Year
- Industry
- Sector
- Revenue
- Competitors
- Data Cleaning

## The notebook covers:

- Dataset profiling and inspection
- Handling missing/invalid values
- Standardizing placeholder values such as -1 and Unknown
- Removing exact duplicate rows
- Cleaning string-based columns
- Correcting data types
- Parsing range-based values
- Standardizing revenue units
- Feature Engineering

### New features were created from existing columns, including:

- Minimum, maximum and average salary
- Minimum and maximum employee count
- Minimum and maximum revenue in millions
- Job state
- Same-state indicator
- Company age
- Simplified job title
- Seniority indicator
- Validation

### The transformed dataset was validated by checking:

- Dataset shape and data types
- Remaining missing values
- Duplicate rows
- Minimum/maximum range consistency
- Transformed feature values

**The final dataset contains 659 rows and 26 columns after cleaning and feature engineering.**

## Files - 

- data_cleaning.ipynb
- cleaned_transformed_DS_jobs.csv


## Tools - 

- Python
- Pandas
- NumPy
- Jupyter Notebook
