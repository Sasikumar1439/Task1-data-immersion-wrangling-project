# Task1-data-immersion-wrangling-project
Retail Store Sales Data Cleaning &amp; Transformation
📊 Data Immersion & Wrangling Project
Retail Store Sales Data Cleaning & Preparation
Project Overview

This project focuses on data immersion, quality assessment, and data wrangling using a Retail Store Sales dataset.

The objective was to transform raw transactional data into a clean, structured, and analysis-ready dataset by identifying and resolving data quality issues such as missing values, duplicates, inconsistent formatting, and outliers.

This project demonstrates foundational skills required for any Data Analyst role — data understanding, cleaning, transformation, and feature engineering.

Objective

To rapidly understand the dataset and perform end-to-end data preparation by:

Exploring and documenting dataset structure

Performing data profiling and quality checks

Cleaning and transforming raw data

Engineering new features for analysis

Delivering a final analysis-ready dataset

Dataset Description

The dataset contains retail transaction records including:

Transaction details

Customer information

Product categories

Pricing and quantity

Payment method

Location

Discount information

Transaction date

Data Quality Assessment

The following issues were identified and addressed:

✔ Missing values in numeric and categorical columns

✔ Duplicate transaction records

✔ Inconsistent text formatting

✔ Non-standard date formats

✔ Outliers in numeric columns

✔ Revenue validation checks

🛠 Data Cleaning & Transformation Steps
1️⃣ Column Standardization

Cleaned column names (lowercase, removed spaces)

2️⃣ Missing Value Treatment

Numeric columns → Filled with median

Categorical columns → Filled with "Unknown"

Boolean fields → Filled with False where applicable

3️⃣ Duplicate Removal

Removed fully duplicated transaction records

4️⃣ Date Transformation

Converted Transaction Date to datetime format

Created new features:

Year

Month

Day

5️⃣ Data Type Corrections

Converted Quantity to integer

Ensured correct numeric formats

6️⃣ Outlier Treatment

Applied IQR method to cap extreme values

7️⃣ Feature Engineering

Time-based features from date column

Revenue consistency validation (Price × Quantity = Total Spent)

📈 Final Output

An analysis-ready dataset with:

Cleaned structure

Standardized formats

No missing values

No duplicates

Engineered time-based features

Improved data consistency

📁 Project Structure
data-immersion-wrangling-project/
│
├── cleaning_script.py
├── cleaned_dataset.csv
├── Retail_Store_Sales_Data_Dictionary.docx
└── README.md
🧰 Tools & Technologies Used

Python

Pandas

NumPy

Git & GitHub

💼 Key Skills Demonstrated

Data Profiling

Data Cleaning & Wrangling

Feature Engineering

Data Validation

Business Understanding of Data

Documentation & Reporting

🚀 Business Value

By transforming raw transactional data into a structured dataset, this project enables:

Time-series sales analysis

Category performance evaluation

Customer behavior insights

Discount impact analysis

Revenue trend monitoring


