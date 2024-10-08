
# Walmart Sales Data Analysis

This project focuses on analyzing Walmart Sales data to identify the highest-performing branches and products, uncover sales trends, and examine customer behavior. The goal is to discover ways to enhance and optimize sales strategies. The dataset was sourced from the [Kaggle Walmart Sales Forecasting Competition.]("https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting")


## Approach Used
1. Data Wrangling
2. Feature Engineering
3. Exploratory Data Analysis(EDA)
4. conclusion
## About The Data

The dataset used in this project was sourced from the [Kaggle Walmart Sales Forecasting Competition]("https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting"). It includes sales transaction data from three distinct Walmart branches situated in Mandalay, Yangon, and Naypyitaw. The dataset comprises 17 columns and 1,000 rows, providing a comprehensive overview of sales activity.

| Column  |Description       | DataType      |
| :----:     | :-------:     | :--- |
| invoice_id| Invoice of the sales made    | VARCHAR(30)    |
| branch    | Branch at which sales were made | VARCHAR(5)     |
| city      | The location of the branch       | VARCHAR(30)    |
| customer_type| The type of the customer      | VARCHAR(30)    |
| gender   | Gender of the customer making purchase| VARCHAR(10)  |
| product_line | Product line of the product solf   | VARCH(100)  |
| unit_price   | The price of each product       | DECIMAL(10, 2) |
| quantity     | The amount of the product sold  | INT            |
| VAT          | The amount of tax on the purchase | FLOAT(6,4)   |
| total        | The total cost of the purchase  | DECIMAL(10, 2) |
| date   | The date on which the purchase was made | DATE    |
| time     | The time at which the purchase was made |TIMESTAMP   |
| payment_method | The total amount paid   | DECIMAL(10, 2) |
| cogs                    | Cost Of Goods sold  | DECIMAL(10, 2) |
| gross_margin_pct | Gross margin percentag| FLOAT(11, 9)  |
| gross_income            | Gross Income        | DECIMAL(10, 2) |
| rating            |Rating                | FLOAT(2, 1)    |


## Business Questions To Answer
### Generic Question
1. How many unique cities does the data have?
2. In which city is each branch?

### Product
1. How many unique product lines does the data have?
2. What is the most common payment method?
3. What is the most selling product line?
4. What is the total revenue by month?
5. What month had the largest COGS?
6. What product line had the largest revenue?
5. What is the city with the largest revenue?
6. What product line had the largest VAT?
7. Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales
8. Which branch sold more products than average product sold?
9. What is the most common product line by gender?
12. What is the average rating of each product line?

### Sales
1. Number of sales made in each time of the day per weekday
2. Which of the customer types brings the most revenue?
3. Which city has the largest tax percent/ VAT (**Value Added Tax**)?
4. Which customer type pays the most in VAT?

### Customer
1. How many unique customer types does the data have?
2. How many unique payment methods does the data have?
3. What is the most common customer type?
4. Which customer type buys the most?
5. What is the gender of most of the customers?
6. What is the gender distribution per branch?
7. Which time of the day do customers give most ratings?
8. Which time of the day do customers give most ratings per branch?
9. Which day fo the week has the best avg ratings?
10. Which day of the week has the best average ratings per branch

##  Analysis List
1. Product Analysis

> Conduct analysis on the data to understand the different product lines, the products lines performing best and the product lines that need to be improved.

2. Sales Analysis

> This analysis aims to answer the question of the sales trends of product. The result of this can help use measure the effectiveness of each sales strategy the business applies and what modificatoins are needed to gain more sales.

3. Customer Analysis

> This analysis aims to uncover the different customers segments, purchase trends and the profitability of each customer segment.
