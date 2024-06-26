## Ecommerce Purchases Project EDA

### Project Overview

The "Ecommerce Purchases Project EDA" is an exploratory data analysis project aimed at uncovering insights and patterns within an e-commerce purchase dataset. This project involves loading the dataset, performing various data analyses, and deriving meaningful conclusions from the data.

### Key Features and Analysis

1. **Dataset Overview:**
   - **Rows and Columns:** The dataset contains 10,000 rows and 14 columns, including details like Address, Lot, AM or PM, Browser Info, Company, Credit Card, CC Exp Date, CC Security Code, CC Provider, Email, Job, IP Address, Language, and Purchase Price.
   - **Data Types:** The dataset includes a mix of object, int64, and float64 data types.
   - **Missing Values:** The dataset has no missing values.

2. **Basic Data Exploration:**
   - **Top and Bottom Rows:** Displaying the top 10 and bottom 10 rows of the dataset.
   - **Column Data Types:** Checking the data type of each column.
   - **Memory Usage:** Reviewing the memory usage of the dataset.

3. **Statistical Analysis:**
   - **Highest and Lowest Purchase Prices:** Identifying the maximum and minimum purchase prices in the dataset.
   - **Average Purchase Price:** Calculating the mean purchase price.

4. **Categorical Analysis:**
   - **Language Analysis:** Determining the number of people who have French ('fr') as their language.
   - **Job Title Analysis:** Finding the number of people whose job title contains the word 'engineer'.
   - **Credit Card Analysis:**
     - Number of people with Mastercard as their credit card provider who made a purchase above $50.
     - Number of people with credit cards expiring in 2020.

5. **Email Analysis:**
   - Finding the email of the person with a specific IP address (132.207.160.22).
   - Finding the email of the person with a specific credit card number (4664825258997302).
   - Determining the top 5 most popular email providers.

6. **Time Analysis:**
   - Number of purchases made during AM and PM.

### Summary

This project provided a comprehensive look into e-commerce purchase data, enabling the extraction of valuable insights such as purchasing patterns, credit card usage, and popular email providers. It served as an excellent exercise in exploratory data analysis using Python and pandas, highlighting the importance of data cleaning, analysis, and interpretation.
