Task 1: Data Cleaning and Preprocessing
Overview
This repository contains the solution to Task 1 of the Data Analyst Internship, which involved cleaning and preprocessing a real-world dataset using Python (Pandas). The goal was to transform a raw dataset into a clean, structured format ready for analysis or modeling.

Dataset
Name: CAR DETAILS FROM CAR DEKHO
Source: Kaggle
Description:
This dataset includes information about used cars listed on CarDekho. It features variables such as car name, year of purchase, selling price, present price, fuel type, seller type, transmission type, and number of previous owners.

Objectives
Identify and handle missing values

Remove duplicate records

Standardize column names and text formatting

Convert columns to appropriate data types

Prepare a clean dataset suitable for further analysis

Files Included
File	Description
CAR DETAILS FROM CAR DEKHO.csv	Raw dataset
cleaned_car_data.csv	Cleaned and processed dataset
preprocessing.ipynb	Jupyter notebook with detailed preprocessing steps
preprocessing.py	Python script containing the same logic for reuse
README.md	Documentation of the task and process followed

Data Cleaning Process
1. Data Loading
Loaded the raw dataset using pandas.read_csv().

2. Initial Exploration
Reviewed data using .head(), .info(), and .describe() to understand structure and detect anomalies.

3. Handling Missing Values
Checked for nulls using .isnull().sum().

Verified and handled any missing values based on context.

4. Duplicate Removal
Removed duplicate rows using .drop_duplicates() to ensure data integrity.

5. Column Name Standardization
Renamed column headers to lowercase and replaced spaces with underscores for consistency.

6. Data Type Conversion
Ensured numerical columns were of appropriate types.

Converted year to integer and price-related fields to numeric types.

7. Text Normalization
Standardized categorical values such as fuel type and transmission for uniformity.

8. Outlier Detection (if applicable)
Performed basic inspection for outliers using visual and statistical methods.

Tools and Libraries
Python 3.x

Pandas

Jupyter Notebook / VS Code

Concepts Practiced
Data wrangling using Pandas

Handling missing values and duplicates

Data type correction

Text and format standardization

Dataset preparation for analysis

Notes
This project was completed as part of the Data Analyst Internship task guidelines. All operations were performed using open-source tools. The cleaned dataset can now be used for exploratory analysis, visualization, or predictive modeling.
