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
- What is the impact of discount on quantity purchased and profit

### Exploratory Data Analysis

#### EDA was carried out on the dataset to answer above questions and techniques used included:

- Group the data using .groupby() function and applying .agg() method
- Change data format from long to wide using pd.pivot_table()
- use of value_counts() method
  

### Results and findings
- All product category recorded profit in the review period (2018 - 2021) although no single category is the most profitable YOY and furniture is the least profitable of the categories
- Technology is the most profitable category cummulatively and edges out office suplies only slightly
- Although profit margin fluctuates, all regions still recorded profit for every year in the dataset
- The least profitable region over entire period is the central region and the most profitable is the west
- Although discounts seem to increase sales, profit is impacted negatively

### Recommendation
Based on the analysis, I recommend the following actions
- removing or reducing discounts for furniture and office supplies categories as these categories record losses when discounts are introduced
- similarly, due to impact of discounts on profit for all regions, I recommend a reduction/removal of discounts for all regions especially those running at a loss(central, south and east) 

 


