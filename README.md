# **Walmart Sales Analysis**

![store image](https://github.com/kul-tanvi19/Walmart-Sales-Analysis/assets/172184420/83c3b926-c243-4ea0-af54-5b267dd9b5b3)


## Table of Content
  - [Problem Statement](#Problem-Statement)
  - [Objective](#Objective)
  - [Datasource](#Datasource)
  - [Data Preparation](#Data-Preparation)
  - [Data Analysis](#Data-Analysis)


## Problem Statement
Analyse Walmart Sales data to identify the top performing branches and products, sales patterns of a various products, and understand the customer behavior.


## Objective
The main goal of this project is to get insight from Walmart Sales data to understand the different factors that affect the sales of different branches.


## Datasource
Dataset was provided by Kaggle Walmart Sales Forecasting Competition.

![image](https://github.com/kul-tanvi19/Walmart-Sales-Analysis/assets/172184420/1d5c6079-d2eb-4848-b7a3-29dc3a809dba)


## Data Preparation
- Understanding the data : 
    - Data consists of `17 Columns` and `1000 records`.
    - Column names are as `Invoice ID`,	 `Branch`,	 `City`,	 `Customer type`,  `Gender`,  `Product line`,  `Unit price`,  `Quantity`,  `Tax 5%`,  `Total`,  `Date`,  `Time`,  `Payment`, 
 `cogs`,  `gross margin percentage`,  `gross income`,  `Rating`.
    - This dataset contains the sales transactions from three Walmart branches located in Mandalay, Yangon and Naypyitaw, respectively.
 
- Data Cleaning/Wrangling :
  This is the initial step, where we examine the data to check any NULL or missing or duplicate values and we replace those values using appropriate strategies.
      - Create a database.
      - Import dataset file into SQL Server.
      - Check for null values in entire table. As our table doesn't contain any NULL values.
      - Check for duplicates based on `Invoice ID`. No duplicates in our table.
 
- 
