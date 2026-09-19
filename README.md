# Retail Sales Analysis

## Overview

This project explores a retail sales dataset using Python to identify customer purchasing patterns, product performance, and sales trends.

The analysis applies data cleaning, exploratory data analysis, visualization, pivot tables, correlation analysis, and basic regression techniques to transform raw transaction data into meaningful business insights.

## Objectives

The main goals of this project are to:

* Understand the structure and quality of the retail dataset
* Analyze customer demographics and purchasing behavior
* Compare sales performance across product categories
* Identify monthly and weekday sales patterns
* Explore relationships between numerical variables
* Apply basic regression analysis to visualize trends

## Dataset

The dataset contains 1,000 retail transactions with the following variables:

* Transaction ID
* Date
* Customer ID
* Gender
* Age
* Product Category
* Quantity
* Price per Unit
* Total Amount

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Analysis

### Data Quality & Preparation

The dataset was reviewed for:

* Dataset dimensions
* Duplicate records
* Unique transaction IDs
* Missing values
* Variable data types

Transaction dates were converted into datetime format and additional time-based variables were created for further analysis.

### Customer Analysis

Customer purchasing behavior was analyzed across demographic groups, including:

* Gender
* Age
* Age groups
* Purchase amount

This helped identify differences in purchasing behavior across customer segments.

### Product Performance

Product categories were compared based on:

* Total sales
* Average transaction value
* Quantity sold
* Customer demographics

Pivot tables were also used to compare sales patterns across multiple customer and product dimensions.

### Sales Trends

Sales performance was analyzed over time to identify patterns by:

* Month
* Day of the week
* Product category

These analyses help illustrate when retail activity is strongest and how purchasing patterns change over time.

### Correlation Analysis

Correlation analysis was used to examine relationships among numerical variables, including:

* Age
* Quantity
* Price per Unit
* Total Amount

This provides a quick view of which variables tend to move together.

### Regression Analysis

Basic regression analysis was performed to visualize relationships between selected variables and sales outcomes.

Regression lines were used to identify general trends and better understand how changes in one variable may relate to another.

## Python Techniques Demonstrated

This project demonstrates practical experience with:

* Data cleaning and validation
* Pandas DataFrames
* `groupby()`
* `agg()`
* `sort_values()`
* `value_counts()`
* Pivot tables
* Datetime manipulation
* Data visualization
* Correlation analysis
* Basic regression analysis

## Repository Structure

```text
Retail-Sales-Analysis/
│
├── Retail_Sales_Analysis.ipynb
├── retail_sales_dataset.csv
└── README.md
```

## Business Value

Retail transaction data can provide useful insight into customer behavior, product demand, and sales performance.

This project demonstrates how Python can be used to organize raw transaction data, identify meaningful patterns, and communicate findings through statistical analysis and visualization.
