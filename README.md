Telco Customer Churn - EDA
📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of the Telco Customer Churn dataset.
The analysis includes data cleaning, feature engineering, handling missing values, and churn insights to better understand customer behavior and prepare the dataset for machine learning models.

1.📂 Dataset

Source: Telco Customer Churn dataset (telco.csv)

Key Features:

Customer demographics

Account information

Service subscriptions

Churn status

2.🔎 Steps in Analysis

Data Loading & Inspection

Read CSV into Pandas DataFrame

Checked dataset structure and data types

Data Cleaning

Removed unnecessary columns

Converted TotalCharges to numeric

Handled missing values

Feature Engineering

Created calculate_TotalCharges = tenure × MonthlyCharges

Added difference_TotalCharges column

Exploratory Analysis

Distribution of churn vs. non-churn customers

Summarized key statistics

3.📊 Results & Insights

Identified missing and inconsistent values in billing data

Derived new features to validate TotalCharges

Initial churn distribution shows class imbalance (more non-churn than churn customers)
