📊 Data Cleaning and Preparation Project
This project focuses on cleaning and preprocessing a real-world world development dataset using Python and pandas. The goal is to transform raw, inconsistent data into a structured format suitable for analysis and machine learning.
🔹 Key Steps Performed
Data Loading
Imported dataset from a CSV file into a DataFrame.
Initial Exploration
Viewed sample data using head()
Checked dataset shape and structure using shape and info()
Data Quality Checks
Identified missing values using isnull().sum()
Checked duplicate records using duplicated()
Analyzed distributions using describe(), skew(), var(), and std()
Handling Missing Values
Dropped columns with more than 40% missing values
Filled missing numerical values using mean imputation
Data Cleaning
Converted currency columns (GDP, Health Expenditure, Tourism data) from string to numeric
Removed special characters like commas and dollar signs
Feature Categorization
Separated columns into:
Numerical features
Categorical features
Correlation Analysis
Generated correlation matrix to understand relationships between variables
🔹 Dataset Overview
Total Rows: 2704
Total Columns (after cleaning): 22
Contains economic, demographic, and health-related indicators for multiple countries
🔹 Tools & Technologies
Python
Pandas
Google Colab
🔹 Outcome
The dataset is cleaned, structured, and ready for:
Exploratory Data Analysis (EDA)
Visualization
Machine Learning models
