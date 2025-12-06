#Retail Sales Analysis & EDA

This project performs Data Cleaning and Exploratory Data Analysis (EDA) on the Superstore Sales Dataset. The goal is to identify sales trends, top-performing regions, and best-selling products.

Dataset
* Name:Superstore Sales Dataset (Kaggle).
* File: `train.csv`
* Key Columns: `Order Date`, `Sales`, `Region`, `Category`, `Product Name`.

Tools Used
* Python
* Pandas (Data manipulation)
* Matplotlib / Seaborn (Visualization)

Project Steps

1. Data Loading & Overview
* Loaded data using Pandas.
* Checked data types and structure.
* Calculated basic statistics (Mean, Median) for Sales.

2. Data Cleaning
* Date Parsing: Converted `Order Date` to datetime format.
* Missing Values: Handled missing data (e.g., in Postal Code).
* Consistency: Standardized text columns (e.g., Region names).

3. Exploratory Data Analysis (EDA)
* Seasonality: Identified monthly sales trends 
* Top Regions: Analyzed sales by region 
* Top Products: Identified the top 5 revenue-generating products.
* Visualizations: Created bar charts and trend lines to visualize the results.
