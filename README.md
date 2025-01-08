## Walmart Sales Data Analysis Project

#### This project involves exploring and analyzing Walmart sales data to uncover insights and trends. The dataset includes information about weekly sales, holidays, store types, and economic indicators such as temperature, fuel prices, and unemployment rates. Below is a detailed description of the workflow and objectives.

### Dataset Overview

File Name: Walmart_Sales.csv
# Walmart Sales Data Analysis Project

This project involves exploring and analyzing Walmart sales data to uncover insights and trends. The dataset includes information about weekly sales, holidays, store types, and economic indicators such as temperature, fuel prices, and unemployment rates. Below is a detailed description of the workflow and objectives.

## Dataset Overview

* **File Name:** Walmart_Sales.csv

* **Columns:**

    * **Store:** Unique store identifier.
    * **Date:** Week-end date of the sales record.
    * **Weekly_Sales:** Sales figures for the respective week.
    * **Holiday_Flag:** Indicates if the week includes a major holiday (1 = Yes, 0 = No).
    * **Temperature:** Average temperature during the week.
    * **Fuel_Price:** Fuel price in the region.
    * **CPI:** Consumer Price Index.
    * **Unemployment:** Unemployment rate in the region.

## Project Objectives

* **Data Cleaning:**
    * Remove duplicate rows.
    * Handle missing or null values.
    * Adjust data types for better analysis (e.g., convert Date to datetime).

* **Exploratory Data Analysis (EDA):**
    * Identify sales trends over time.
    * Examine the impact of holidays on weekly sales.
    * Analyze relationships between sales and economic indicators.
    * Visualize store-level performance.

* **Statistical Analysis:**
    * Explore correlations between variables.
    * Conduct comparisons of sales during holidays and non-holidays.

* **Visualizations:**
    * Line charts for sales trends.
    * Boxplots for weekly sales by holiday status.
    * Heatmaps for correlations.
    * Bar charts for store-level sales performance.

## Workflow

**Data Cleaning:**

1. Load the data using Pandas.
2. Remove duplicates using `DataFrame.drop_duplicates()`.
3. Replace or remove null values using `DataFrame.fillna()` or `DataFrame.dropna()`.
4. Convert Date column to datetime format using `pd.to_datetime()`.

**Exploratory Data Analysis:**

1. Calculate total, average, and median weekly sales.
2. Group and aggregate data by store, holiday flag, or date ranges.
3. Visualize trends and patterns using Matplotlib and Seaborn.

## Insights

* Determine which stores generate the most revenue.
* Assess the influence of holidays on sales.
* Analyze how external factors like temperature, fuel price, and unemployment correlate with sales.

## Python Tools Used

* **Pandas:** Data cleaning and manipulation.
* **Matplotlib/Seaborn:** Data visualization.
* **NumPy:** Statistical computations.
Columns:

Store: Unique store identifier.

Date: Week-end date of the sales record.

Weekly_Sales: Sales figures for the respective week.

Holiday_Flag: Indicates if the week includes a major holiday (1 = Yes, 0 = No).

Temperature: Average temperature during the week.

Fuel_Price: Fuel price in the region.

CPI: Consumer Price Index.

Unemployment: Unemployment rate in the region.

### Project Objectives

Data Cleaning:

Remove duplicate rows.

Handle missing or null values.

Adjust data types for better analysis (e.g., convert Date to datetime).

Exploratory Data Analysis (EDA):

Identify sales trends over time.

Examine the impact of holidays on weekly sales.

Analyze relationships between sales and economic indicators.

Visualize store-level performance.

### Statistical Analysis:

Explore correlations between variables.

Conduct comparisons of sales during holidays and non-holidays.

### Visualizations:

Line charts for sales trends.

Boxplots for weekly sales by holiday status.

Heatmaps for correlations.

Bar charts for store-level sales performance.

### Workflow

Data Cleaning:

Load the data using Pandas.

Remove duplicates using DataFrame.drop_duplicates().

Replace or remove null values using DataFrame.fillna() or DataFrame.dropna().

Convert Date column to datetime format using pd.to_datetime().

### Exploratory Data Analysis:

Calculate total, average, and median weekly sales.

Group and aggregate data by store, holiday flag, or date ranges.

Visualize trends and patterns using Matplotlib and Seaborn.

### Insights:

Determine which stores generate the most revenue.

Assess the influence of holidays on sales.

Analyze how external factors like temperature, fuel price, and unemployment correlate with sales.

### Python Tools Used

Pandas: Data cleaning and manipulation.

Matplotlib/Seaborn: Data visualization.

NumPy: Statistical computations.
