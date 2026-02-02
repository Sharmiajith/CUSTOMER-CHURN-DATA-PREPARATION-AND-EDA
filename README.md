📊 Customer Churn Data Preparation & Exploratory Data Analysis (EDA)

📝 Project Overview
This project focuses on data preparation and exploratory data analysis (EDA) for a Customer Churn dataset.
The goal is to understand customer behavior, identify churn patterns, and prepare clean data for further machine learning modeling.

🛠️ Tech Stack & Libraries Used
Python
Pandas – data loading and manipulation
NumPy – numerical operations
Seaborn – statistical data visualization
Matplotlib – plotting and charts
Warnings – suppress unnecessary warnings for clean output

import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
import warnings
warnings.filterwarnings('ignore')

📂 Dataset Description
The dataset contains customer-related information such as:
Demographics (gender, senior citizen, etc.)
Account information (tenure, contract type, payment method)
Service usage details
Billing details (monthly charges, total charges)
Target variable: Churn (Yes / No)

🧹 Data Preparation Steps
Data Loading
Read the dataset using pandas.
Data Type Conversion
Converted numerical columns stored as objects (e.g., TotalCharges) into numeric format.
Handling Missing Values
Identified and handled missing or invalid entries (e.g., blank spaces).
Duplicate Check
Verified there are no duplicate records.
Feature Formatting
Standardized categorical values for consistency.

🔍 Exploratory Data Analysis (EDA)
The following analyses were performed:
📌 Univariate Analysis
Distribution of numerical features like:
tenure
MonthlyCharges
TotalCharges
Count plots for categorical variables.

📌 Bivariate Analysis
Churn vs tenure
Churn vs monthly charges
Churn vs contract type

📌 Visualization Techniques
Bar plots
Histograms
Box plots
Correlation heatmap

📈 Key Insights
Customers with shorter tenure are more likely to churn.
Higher monthly charges show a higher churn tendency.
Customers with month-to-month contracts have higher churn rates.
Long-term contracts are associated with better customer retention.

🎯 Conclusion
This EDA helps in:
Understanding churn-driving factors
Identifying important features for modeling
Ensuring high-quality, clean data for machine learning pipelines
