# Company Sales Analysis Dashboard

## Table of Content

  - [Project Overview](#project-overview)
  - [Data Sources](#data-sources)
  - [Tools](#tools)
  - [Data Cleaning and Preparation](#data-cleaning-and-preparation)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Results and Findings](#results-and-findings)
  - [Recommendations](#recommendations)
  - [Limitations](#limitations)
  - [References](#references)
### Project Overview

This data analysis project aims to provide insights into the sales performance of a company over three years. By analyzing various aspect of the sales data, we seek to identify the top performing products, sales channels and sales person and generally gain a deeper understanding of the company's financial performance.

### Data Sources

Sales Data: The primary dataset used for this analysis is the "salesdata.xlsx", "budget.xlsx", "photos.xlsx", and "product.xlsx" files, containing detailed information about each sale made by company and the specific products which the company deals in.

### Tools

- PowerBI - This was used for all steps in this report


### Data Cleaning and Preparation

The Initial dataset provided was clean and thus there was little or no much work done to this regards.
Due to the fact that our data came from more than one dataset, there was need to merge queries from different datasets and different steps were taken within the individual dataset, so during the preparation phase, we performed the following tasks:

- Sales Data
  - A mathematical formular was introduced to create a new column
  - Unnecessary columns were removed.

- Product Data
  - Product photos were added to the table by merging queries from the photos dataset.

- Budget Data
  - Null and irrelevant rows were filtered out
  - Dataset was rearranged by unpivoting columns

### Exploratory Data Analysis
 - How does our revenue fare against our budget?
 - When is our peak sales period?
 - Which ProductGroup generates the most revenue?
 - What is the contribution of our sales channel to our overall revenue?
 - How do our Supervisors and Salesperson perform with respect to revenue and orders?
 - what are the percentage contribution of our Productcategory to our overall revenue?
 - Who are our top 3 salesperson?
 - Rank of all our salespersons and their percentage contribution to the total revenue

### Results and Findings
The analysis results are as follows:
1. The company's revenue increases across each quarter every year but recorded a it's lowest revenue in Q1 of 2021.
2. Wheat flour is the best performing ProductGroup and Food products performed better than drink products in terms of revenue generated.
3. There is need for more marketing efforts towards our online stores so as to improve the revenue it generates.

### Recommendations
Based on the analysis, the following actions are recommended:
- Invest in marketing and promotions during the first quarter of every year to maximize promotions.
- Focus on expanding and promoting drink category products.
  
### Limitations
I had to remove all zero and null values from budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers but we can still see that there is a positive correlation between both budget and revenue.

### References
  1. Leonardo Karpainski
  2. Pragmatic works
