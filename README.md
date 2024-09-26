# LILO FOOD AND BEVERAGES SALES ANALYSIS

## Table of content

 -[Project overview](#project-overview)
 
 -[Data source](#data-source)

 -[Tools](#tools)

 -[Data cleaning/preparation](##data-cleaning-preparation)

 -[Exploratory Data Analysis](#exploratory-data-analysis)

 -[Data Analysis](#data-analysis)

 -[Result/Findings](#result-findings)

 -[Recommendation](#recommendation)

 -[Limitation](#limitation)
 
 



 
  


 
### Project overview

This data analysis project aims to provide insight into sales performance of LILO Food&Beverage company over the past year. By analyzing various aspect of the sales data                      we seek to identify trends, make data driven recommendation and gain a deeper understanding of the company performance.

![Screenshot 2024-09-26 191624](https://github.com/user-attachments/assets/87cf1259-d927-4ff9-be10-4e4e2cd7ad38)








### Data source

Sales Data: The primary dataset used for this analysis is the "Sales_data & Product.xlsx" file, containing detailed information about each sales made by the company.

### Tools

- Excel
- Power query - Data cleaning
- Power pivot - Data analysis


### Data cleaning/Preparation

In the initial data preparation phase, i performed the following tasks:
 1. Data loading and inspection using power query
 2. Handling missing value
 3. Data cleaning and formatting
 4. Data linking
 5. Data analysis


### Exploratory Data Analysis

EDA involved exploring the sales data to answer key question, such as:

1. What is the total revenue?
2. What is the total number of order placed?
3. What is the average ticket price?
4. what are the top 10 product that generated the most revenue?
5. what are the top 3 salesperson by order and revenue?
6. Total order by product category?
7. Monthly distribution of revenue and order?
8. Distribution of revenue by channel?
9. Total revenue by product category?

### Data Analysis

``` DAX
Round(Divide(Total revenue, Total order, "0"),0) for average ticket price in sales dataset
distictcount(total order) in sales dataset
```

### Result/Findings

1. Lilo food&beverage company makes 18 million in revenue from 52.6 thousand orders a year
2. Top 3 salespersons are carla ferreira, julio lima and Gustavo gomes in terms of revenue and order
3. Food has more order than drinks
4. The month october has the highest in distibution and order
5. Quarter 4 has the highest revenue and order

### Recommendation

Based on the analysis we recommend the following action:
1.why does october has the highest distribution and order
2.flour generate the most revenue therefore the company should invest more on that product
3.The top 3 salepersons should share their insight with their colleague
4.Food makes the highes revenue so the company should invest more on their food product

### Limitation

Some rows where blank and had to be removed





    
