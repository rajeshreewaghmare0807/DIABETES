
# DIABETES
Diabetes dataset preprocessing and exploratory data analysis using Python, including data inspection, missing-value checking, statistical analysis, visualization, and feature scaling.
# Diabetes Data Preprocessing

## 1. Project Overview

This project focuses on cleaning, exploring, and preprocessing a diabetes dataset using Python. The goal is to understand the data and prepare it for further data analysis and machine learning.

## 2. Libraries Used

The following Python libraries are used:

* **Pandas** – for data loading and data manipulation
* **NumPy** – for numerical operations
* **Scikit-learn** – for data preprocessing and scaling
* **Seaborn** – for data visualization
* **Matplotlib** – for creating graphs and plots

## 3. Loading the Dataset

The `diabetes.csv` dataset is loaded using Pandas. The `head()` function is used to display the first few records and understand the structure of the dataset.

## 4. Dataset Information

The dataset contains **768 records and 9 columns**.

The main columns are:

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age
* Outcome

The `Outcome` column represents the diabetes result.

## 5. Checking Data Types and Missing Values

The `info()` function is used to check the number of records, columns, and data types.

The `isnull().sum()` function is used to check for missing values. In this dataset, all nine columns contain **768 non-null values**, so no missing values are detected by this check.

## 6. Descriptive Statistics

The `describe()` function is used to calculate statistical information such as:

* Count
* Mean
* Standard deviation
* Minimum value
* Maximum value
* Quartiles

This helps in understanding the distribution and range of the numerical variables.

## 7. Outlier Analysis

Boxplots are created for all columns to visually identify possible outliers in the dataset.

The boxplots help to understand the spread of each variable and detect unusually high or low values.

## 8. Data Preprocessing

Scikit-learn preprocessing techniques are imported, including:

* **MinMaxScaler**
* **StandardScaler**

These techniques can be used to scale numerical features and bring them into a suitable range for machine learning models.

## 9. Objective

The main objective of this project is to:

* Understand the diabetes dataset
* Check data quality
* Identify missing values
* Analyze statistical characteristics
* Detect possible outliers
* Prepare the data for further analysis and machine learning

## 10. Conclusion

The diabetes dataset is explored and checked for data quality using Python. Statistical analysis and visualization are performed to understand the data. The preprocessing tools provide a foundation for preparing the dataset for further machine learning applications.

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

