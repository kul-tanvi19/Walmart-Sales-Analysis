# **Walmart Sales Analysis**

![store image](https://github.com/kul-tanvi19/Walmart-Sales-Analysis/assets/172184420/83c3b926-c243-4ea0-af54-5b267dd9b5b3)


## Table of Content
  - [Problem Statement](#Problem-Statement)
  - [Questions to Answer](#Questions-to-Answer)
  - [Objective](#Objective)
  - [Datasource](#Datasource)
  - [Data Preparation](#Data-Preparation)
  - [Data Analysis](#Data-Analysis)


## Problem Statement
Analyse Walmart Sales data to identify the top performing branches and products, sales patterns of a various products, and understand the customer behavior.


## Questions to Answer
### General Questions :
  1. How many distinct cities are present in the dataset?
  2. In which city is each branch situated?

### Product Analysis Questions :
  1. How many distinct product lines are there in the dataset?
  2. What is the most common payment method?
  3. What is the most selling product line?
  4. What is the total revenue by month?
  5. Which month recorded the highest Cost of Goods Sold (COGS)?
  6. Which product line generated the highest revenue?
  7. Which city has the highest revenue?
  8. Which product line incurred the highest VAT?
  9. Retrieve each product line and add a column product_category, indicating 'Good' or 'Bad,' based on whether its sales are above the average.
  10. Which branch sold more products than average product sold?
  11. What is the most common product line by gender?
  12. What is the average rating of each product line?

### Customer Analysis Questions :
  1. How many unique customer types does the data have?
  2. How many unique payment methods does the data have?
  3. Which is the most common customer type?
  4. Which customer type buys the most? or Identify the customer type that generates the highest revenue.
  5. What is the gender of most of the customers?
  6. What is the gender distribution per branch?
  7. Which time of the day do customers give most ratings?
  8. Which time of the day do customers give most ratings per branch?
  9. Which day of the week has the best avg ratings?
  10. Which day of the week has the best average ratings per branch?

### Sales Analysis Questions :
  1. Number of sales made in each time of the day per weekday
  2. Which city has the largest tax percent/ VAT (Value Added Tax)?
  3. Which customer type pays the most VAT?

## Objective
The main goal of this project is to get insight from Walmart Sales data to understand the different factors that affect the sales of different branches.


## Datasource
Dataset was provided by Kaggle Walmart Sales Forecasting Competition.

![image](https://github.com/kul-tanvi19/Walmart-Sales-Analysis/assets/172184420/1d5c6079-d2eb-4848-b7a3-29dc3a809dba)


## Data Preparation
  - Understanding the data : 
      - Data consists of `17 Columns` and `1000 records`.
      - Column names are as ***Invoice ID***,	 ***Branch***,	 ***City***,	 ***Customer type***,  ***Gender***,  ***Product line***,  ***Unit price***,  ***Quantity***,  ***Tax 5%***,  ***Total***,  ***Date***,  ***Time***,  ***Payment***, ***cogs***,  ***gross margin percentage***,  ***gross income***,  ***Rating***.
      - This dataset contains the sales transactions from three Walmart branches located in Mandalay, Yangon and Naypyitaw, respectively.
 
  - Data Cleaning/Wrangling :
    </br>
    </br>
    This is the initial step, where we examine the data to check any NULL or missing or duplicate values and we replace those values using appropriate strategies.
    
       - Create a database.
       - Import dataset file into SQL Server.
       - Check for null values in entire table. As our table doesn't contain any NULL values.
       - Check for duplicates based on `Invoice ID`. No duplicates in our table.

 - Feature Engineering :
   </br>
   </br>
   This allows us to generate new columns from existing ones.

       - 
