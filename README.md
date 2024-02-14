# A Comprehensive SQL Examination of Credit Card Activity in Fintech for Fraud Detection
## Executive Summary
This research project uses SQL skills to analyze historical credit card transactions and consumption patterns to identify potential fraudulent activities. The study involves data modeling, engineering, and analysis using PostgreSQL, focusing on creating an entity relationship diagram (ERD), designing a database schema, importing data, and generating queries to uncover fraud trends. 

## Methodology 
##### 1. Data Modeling:
- Create an ERD to represent the relationships among tables, considering CSV files for credit card and transaction data.
- Define database model details, including VARCHAR (20) for credit card numbers and TIMESTAMP for transaction dates.

##### 2. Data Engineering:
- Develop a PostgreSQL database schema based on the ERD, specifying data types, primary keys, and foreign keys.
- Import data from provided CSV files into the created schema.

##### 3. Data Analysis - Part 1:
- Identify transactions less than $2.00 per cardholder to detect potential credit card hacks.
- Determine the top 100 highest transactions between 7:00 am and 9:00 am, investigating possible anomalies.
- Evaluate if there's a correlation between the time frame and the occurrence of fraudulent transactions.
- Identify the top 5 merchants prone to small transaction hacks.

##### 4. Data Analysis - Part 2:
- Verify potential fraudulent transactions for cardholders with IDs 2 and 18.
- Create time series line plots for these cardholders to observe consumption patterns.
- Investigate corporate credit card misuse in Q1 2018 for cardholder ID 25 using hvPlot box plots.

##### 5. Challenge:
- Implement Python functions using standard deviation and interquartile range to identify outliers for any cardholder.
