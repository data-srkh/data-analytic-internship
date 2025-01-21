# data-analytic-internship
## Task 1

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
---

# Task 2

### 1. Data Loading and Initial Exploration  
- Loaded and explored data from `QVI_data.csv`.  
- Reviewed data structure, column names, and initial statistics to understand its contents.  



### 2. Filtering Trial Stores  
- Filtered trial stores (77, 86, and 88) for detailed analysis.  
- Added a new column to group transactions by month for easier aggregation.  



### 3. Aggregating Monthly Metrics  
- Calculated key monthly metrics for trial stores, including:  
  - Total sales.  
  - Total unique customers.  
  - Total transactions.  
  - Average transactions per customer.  


### 4. Finding Control Stores  
- Identified potential control stores for trial store comparison by analyzing correlations of monthly metrics.  
- Focused on metrics such as total sales and total customers to determine similarity.  



### 5. Comparing Trial and Control Stores  
- Compared key performance metrics between trial and control stores:  
  - Total unique customers.  
  - Average transactions per customer.  
- Observed no significant differences due to the absence of suitable control stores with sufficient data overlap.  
