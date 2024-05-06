## Sales Analysis
 
### Project Overview

This project aims to provide insight into the sales/profit performance of a company over a period between 2018 and 2021. By analysing these metrics for different dimensions, we aim to gain a depper undertsanding of the company's performance, identify trends and make data-driven recommendations.

### Data Source

The primary data set used for this "orders.csv" containing the company's order transactions between 2018 and 2021

### Tools used

- Python specicifically pandas module was used to clean and analyse the data
- The web application;Jupyter notebook was used to create and run the Python code

### Data Cleaning/Preparation

Some of the tsaks performed in this phase:

- Load and inspect data
- Rename column
- Change column data type
- Drop unwanted columns

### Project Goal and Questions

#### The goal of any company is to maximize profit, consequently, the project aims to answer the following questions:

- What is the most profitable product category
- What is the most profiable region
- What is the relationship between sales value and profit
- -What is the impact of discount on quantity purchased and profit

### Exploratory Data Analysis

#### EDA was carried out on the dataset to answer above questions and techniques used included:

- Group the data using .groupby() function and applying .agg() method
- Change data format from long to wide using pd.pivot_table()
- use of values_counts() method


 


