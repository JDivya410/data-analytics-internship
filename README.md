# Data Analytics Internship

## Task 1: EDA on Retail Sales Data
Exploratory data analysis of a retail sales dataset (1,000 transactions, 2023) using
Python, pandas, matplotlib and seaborn.

**Files**
- `Task1_Retail_EDA.ipynb`: the full analysis notebook
- `retail_sales_dataset.csv`: dataset (Kaggle, Retail Sales Dataset, CC0 license)

**Main findings**
1. About 40% of transactions (price 300 or 500) generate 88.4% of revenue.
2. Revenue is highest on Saturdays and in Q4, and lowest in September.
3. Age alone does not predict spending, but age combined with product category shows
   clear differences.

## Task 3: Cleaning Data
Cleaned a dirty cafe sales dataset (10,000 rows) with missing values, ERROR/UNKNOWN
placeholders and wrong data types. Recovered missing numbers from Total = Quantity x Price.
Missing/invalid cells dropped from 10,082 to 460 (the remaining ones are missing dates).

**Files**
- `Task3_Data_Cleaning.ipynb`: the cleaning notebook
- `cleaned_cafe_sales.csv`: the cleaned dataset

## Level 2, Task 1: House Price Prediction
Linear regression on 545 houses (area, bathrooms, air conditioning, furnishing and more)
using Python, pandas and scikit-learn. Test R² = 0.653, RMSE ≈ 1.32M. Main price
drivers: bathrooms, air conditioning and preferred area. The model under-predicts
expensive houses.

**Files**
- `Task4_House_Price_Prediction.ipynb`: the analysis and model notebook
- `Housing.csv`: dataset (Kaggle, Housing Prices Dataset, CC0 license)

## Tasks completed
- [x] Level 1, Task 1: EDA on Retail Sales Data
- [x] Level 1, Task 3: Cleaning Data
- [x] Level 2, Task 1: Predicting House Prices with Linear Regression
