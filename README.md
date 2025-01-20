# data-analytic-internship
## Internship Tasks: Data Cleaning and Preprocessing

This project focuses on cleaning and preprocessing data for analysis. Here's a breakdown of the tasks performed:

**1. Data Loading and Initial Exploration:**

* Loaded purchase data from 'QVI_purchase_behaviour.csv' and transaction data from 'QVI_transaction_data.xlsx' into pandas DataFrames.
* Performed initial data exploration using `info()` and `describe()` to understand the structure, data types, and basic statistics of the datasets.

**2. Outlier Detection and Removal:**

* Employed the Z-score method to identify outliers in both datasets.
* Removed outliers based on a threshold of 3 standard deviations from the mean.
* Created new DataFrames (`purchase_df` and `transaction_df`) without the outliers.

**3. Data Type Correction:**

* Converted relevant columns in both DataFrames to their appropriate data types using `pd.to_numeric()` and `pd.to_datetime()`.
* This ensured data consistency and facilitated further analysis.
