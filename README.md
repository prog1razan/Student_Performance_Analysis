# Student Performance Analysis

A data analysis project that explores student performance data using Python, with a focus on data cleaning, exploratory data analysis, visualization, correlation analysis, and feature preparation.

## 📌 Overview

This project analyzes student performance data from two secondary schools.

The main objective is to understand the dataset, clean and prepare the data, explore relationships between variables, and identify important features that can be used to predict students' final Math grades.

The project also introduces the concept of **Supervised Learning** and **Regression**, since the target variable is a numerical final Math grade.

## 🎯 Problem Formulation

The main question explored in this project is:

> **How can we predict a student's final Math grade based on the available data?**

The problem is considered:

- **Supervised Learning** — because the dataset contains a known target value.
- **Regression** — because the target is a numerical value representing the student's final Math grade.

## 📊 Dataset

The dataset contains information about students from two secondary schools and includes academic, demographic, and other student-related attributes.

The dataset is loaded directly from a CSV file using Pandas.

During the analysis, the data is examined for:

- Missing values
- Incorrect data formats
- Duplicate records
- Outliers
- Relationships between variables
- Correlations between features

## 🧹 Data Cleaning

The notebook covers several important data-cleaning concepts, including:

- Inspecting the dataset using `df.info()`
- Identifying missing values
- Converting `"?"` values into `NaN`
- Handling missing data
- Correcting data types
- Removing duplicate records
- Data standardization
- Data normalization

## 🔍 Exploratory Data Analysis

Exploratory Data Analysis (EDA) is used to better understand the dataset and discover patterns.

The project explores:

- Individual variables
- Relationships between variables
- Weak and strong relationships
- Potential outliers
- Correlations between features

Data visualization is performed using **Matplotlib** and **Seaborn**.

## ⚙️ Feature Engineering

The project introduces feature engineering concepts, including:

- Constructing new features
- Combining or transforming existing features
- Selecting relevant features for prediction

The goal is to identify the variables that may be useful for predicting the final Math grade.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## 📚 Concepts Covered

- Data Loading
- Data Exploration
- Data Cleaning
- Missing Data Handling
- Data Standardization
- Data Normalization
- Duplicate Removal
- Outlier Detection
- Exploratory Data Analysis (EDA)
- Data Visualization
- Correlation Analysis
- Feature Engineering
- Feature Selection
- Introduction to Regression

## 📁 Project Structure

```text
Student-Performance/
│
├── Student_Performance.ipynb
└── README.md
