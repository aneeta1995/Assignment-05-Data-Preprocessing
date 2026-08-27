# Data Preprocessing Project

## Project Overview

This project focuses on preparing an employee dataset for data analysis and machine learning. The main goal is to improve the quality and consistency of the data by handling missing values, duplicates, outliers, and categorical data.

## Dataset

The dataset contains employee information such as:
- Company
- Age
- Salary
- Place
- Country
- Gender

## Data Preprocessing

The following steps were performed:
- Explored the dataset and checked unique values.
- Performed basic statistical analysis.
- Renamed the columns for easier use.
- Identified and handled missing values.
- Replaced age values of 0 with NaN and treated the missing values.
- Removed duplicate rows.
- Identified outliers using boxplots.

## Data Analysis

- Filtered employees with age greater than 40 and salary less than 5000.
- Created a chart to show the relationship between age and salary.
- Counted employees from each place and represented the results visually.

## Data Encoding

Categorical columns such as Company, Place, and Country were converted into numerical values using one-hot encoding.

## Feature Scaling

Applied:
- StandardScaler
- MinMaxScaler

to scale the numerical features.

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Conclusion

This project demonstrates the basic steps involved in cleaning, preparing, analyzing, and transforming data so that it can be used effectively for further analysis and machine learning.
