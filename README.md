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

## Level 1, Task 2: Customer Segmentation
RFM analysis and K-Means clustering (K = 4) on 5,878 customers of a UK online retailer
(Online Retail II UCI, 2009-2011). Segments: Champions (15% of customers, 69% of revenue),
Loyal Regulars, Recent Low-Spenders and Lapsed/Lost, with marketing actions for each.

**Files**
- `Task6_Customer_Segmentation.ipynb`: the analysis notebook
- Dataset: Online Retail II UCI (Kaggle), not included because of its size

## Task 3: Cleaning Data
Cleaned a dirty cafe sales dataset (10,000 rows) with missing values, ERROR/UNKNOWN
placeholders and wrong data types. Recovered missing numbers from Total = Quantity x Price.
Missing/invalid cells dropped from 10,082 to 460 (the remaining ones are missing dates).

**Files**
- `Task3_Data_Cleaning.ipynb`: the cleaning notebook
- `cleaned_cafe_sales.csv`: the cleaned dataset

## Level 1, Task 4: Sentiment Analysis
Classified tweets as Positive, Negative or Neutral (69,061 tweets after cleaning) using
TF-IDF with Naive Bayes and Logistic Regression. Data was split by tweet ID to prevent
leakage. Logistic Regression reached 0.609 accuracy (macro F1 0.60), Naive Bayes 0.605.

**Files**
- `Task7_Sentiment_Analysis.ipynb`: the analysis notebook
- Dataset: Twitter Sentiment Analysis (Kaggle)

## Level 2, Task 1: House Price Prediction
Linear regression on 545 houses (area, bathrooms, air conditioning, furnishing and more)
using Python, pandas and scikit-learn. Test R² = 0.653, RMSE ≈ 1.32M. Main price
drivers: bathrooms, air conditioning and preferred area. The model under-predicts
expensive houses.

**Files**
- `Task4_House_Price_Prediction.ipynb`: the analysis and model notebook
- `Housing.csv`: dataset (Kaggle, Housing Prices Dataset, CC0 license)

## Level 2, Task 2: Wine Quality Prediction
Classified wine quality (low, medium, high) from the chemical properties of 5,329 wines
(after removing 1,168 duplicates) using Random Forest, SGD and SVC. Random Forest was
best (accuracy 0.62, macro F1 0.61). Alcohol, density and volatile acidity were the most
important features.

**Files**
- `Task5_Wine_Quality.ipynb`: the analysis and models
- `winequalityN.csv`: dataset (Kaggle, Wine Quality)

## Tasks completed

- [x] Level 1, Task 1: EDA on Retail Sales Data
- [x] Level 1, Task 2: Customer Segmentation Analysis
- [x] Level 1, Task 3: Cleaning Data
- [x] Level 1, Task 4: Sentiment Analysis
- [x] Level 2, Task 1: Predicting House Prices with Linear Regression
- [x] Level 2, Task 2: Wine Quality Prediction
