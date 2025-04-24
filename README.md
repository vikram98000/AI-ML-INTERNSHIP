# AI-ML-INTERNSHIP
# Titanic Dataset Preprocessing & Visualization

This project focuses on cleaning and preprocessing the Titanic dataset, with a particular emphasis on converting categorical data to numerical form, normalizing numerical columns, visualizing data distributions, and handling outliers.

## 📂 Project Overview

The main goals of this project were:

- Cleaning and preparing the Titanic dataset for analysis or modeling.
- Converting categorical variables into numerical values.
- Normalizing the Age and Fare columns to standardize the data.
- Visualizing the distribution of key numerical features.
- Detecting and removing outliers using boxplots.

## 📊 Dataset

The dataset used is the classic Titanic dataset from Kaggle, which contains information about passengers aboard the RMS Titanic, such as:

- Name, Sex, Age
- Ticket, Fare, Cabin, Embarked
- Passenger Class, Survival status

## 🧹 Data Cleaning Steps

1. Missing Values Handling:
   - Checked and handled missing values in critical columns like Age, Fare, Embarked.

2. Categorical Encoding:
   - Converted categorical columns such as Sex and Embarked into numerical values using encoding techniques.



## 📏 Normalization

- Applied normalization techniques on the Age and Fare columns to scale the values for better analysis and model performance.

## 📦 Outlier Detection

- Visualized Age and Fare using boxplots to observe the spread and detect outliers.
- Removed the identified outliers to maintain dataset consistency and reliability.

## 📈 Visualizations

- Used boxplots to visualize distributions and outliers in the Age and Fare columns before and after cleaning.

## 📁 Files Included

- titanic_cleaning.ipynb — The Jupyter Notebook containing all preprocessing and visualization steps.
- README.md — This file.



## 🧠 Requirements

To run the notebook, you will need:

```bash
Python 3.x
pandas
numpy
matplotlib
seaborn
