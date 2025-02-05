# E-Commerce-Analysis
This project performs exploratory data analysis on an e-commerce dataset, exploring customer behavior, purchase patterns, and attributes like job titles and languages. Key insights include the highest/lowest purchase prices, popular email providers, and language preferences using pandas and data-cleaning techniques.
# E-Commerce Purchase Data Analysis (EDA)

## Overview
This project involves performing **Exploratory Data Analysis (EDA)** on a dataset containing customer purchase data from an e-commerce platform. The dataset includes various details such as customer information, purchase details, and credit card data. Through this analysis, we aim to uncover patterns and insights related to customer behavior, purchasing trends, and other valuable metrics.

## Dataset Description
The dataset consists of **10,000 entries** and **14 columns** with the following key fields:

- **Address**: The address of the customer.
- **Lot**: Lot or a unique identifier associated with the customer's purchase.
- **AM or PM**: Time of day when the purchase was made (AM or PM).
- **Browser Info**: Information about the browser used for the purchase.
- **Company**: The company to which the customer belongs.
- **Credit Card**: The customer's credit card number.
- **CC Exp Date**: The expiration date of the credit card.
- **CC Security Code**: The security code of the customer's credit card.
- **CC Provider**: The credit card provider (e.g., Visa, Mastercard).
- **Email**: The customer's email address.
- **Job**: The job title of the customer.
- **IP Address**: The IP address from which the purchase was made.
- **Language**: The language spoken by the customer (e.g., 'en' for English, 'fr' for French).
- **Purchase Price**: The total purchase price made by the customer.

### Data Types:
- **Object**: 11 columns (categorical or string data).
- **Int64**: 2 columns (numerical data for credit card and security code).
- **Float64**: 1 column (numerical data for purchase price).

### Example Columns and Data Types:
| Column            | Data Type  | Description                                |
|-------------------|------------|--------------------------------------------|
| Address           | Object     | Customer's address                         |
| Lot               | Object     | Unique identifier for the customer's purchase |
| AM or PM          | Object     | Purchase time (AM/PM)                      |
| Browser Info      | Object     | Information about the browser used         |
| Company           | Object     | Company to which the customer belongs      |
| Credit Card       | Int64      | Customer's credit card number              |
| CC Exp Date       | Object     | Expiration date of the credit card         |
| CC Security Code  | Int64      | Credit card security code                  |
| CC Provider       | Object     | Credit card provider                       |
| Email             | Object     | Customer's email address                   |
| Job               | Object     | Job title of the customer                  |
| IP Address        | Object     | IP address from which the purchase was made|
| Language          | Object     | Language spoken by the customer            |
| Purchase Price    | Float64    | Total price of the purchase                |

## Questions Addressed
The following questions were answered through the exploratory data analysis:
1. **Display Top 10 Rows of The Dataset**
2. **Check Last 10 Rows of The Dataset**
3. **Check Datatype of Each Column**
4. **Check Null Values in the Dataset**
5. **How Many Rows and Columns Are There in Our Dataset?**
6. **Highest and Lowest Purchase Prices**
7. **Average Purchase Price**
8. **How Many People Have French ('fr') as Their Language?**
9. **How Many Job Titles Contain 'Engineer'?**
10. **How Many People Have Mastercard as Their Credit Card Provider and Made a Purchase Above 50?**
11. **Find the Email of the Person with the Following Credit Card Number: 4664825258997302**
12. **How Many People Purchase During the AM and How Many Purchase During PM?**
13. **How Many People Have a Credit Card That Expires in 2020?**
14. **What Are the Top 5 Most Popular Email Providers?**

## Getting Started
To begin analyzing the dataset, follow these steps:

git clone https://github.com/03Pranay14/E-Commerce-Analysis.git

cd E-Commerce-Analysis

