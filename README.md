# Walmart-Sales-Data-Analysis

## Project Overview 
This project is an end-to-end data analysis solution designed to extract critical business insights from Walmart sales data. We utilize Python for data processing and analysis, SQL for advanced querying, Power BI for presenting key insights, and structured problem-solving techniques to solve key business questions. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Project Steps - 

#### 1. Setting Up the Environment
Tools Used: Visual Studio Code (VS Code), Python, SQL (MS SQL Server)

Goal: Create a structured workspace within VS Code and organize project folders for smooth development and data handling.


#### 2. Download Walmart Sales Data from Kaggle
Dataset Link: [Walmart Sales Dataset](https://www.kaggle.com/najir0123/walmart-10k-sales-datasets)

Storage: Save the dataset in respective folder for later access.


#### 3. Install Required Libraries and Load Data
Libraries - Install necessary Python libraries using:
pip install pandas numpy sqlalchemy pyodbc

Loading Data: Read the data into a Pandas DataFrame for initial analysis and transformations.


#### 4. Explore the Data
Goal: Conduct an initial data exploration to understand data distribution, check column names, types, and identify potential issues.

Analysis: Use functions like .info(), .describe(), and .head() to get a quick overview of the data structure and statistics.


#### 5. Data Cleaning
#### Remove Duplicates: Identify and remove duplicate entries to avoid skewed results.
#### Handle Missing Values: Drop rows or columns with missing values if they are insignificant; fill values where essential.
Fix Data Types: Ensure all columns have consistent data types (e.g., dates as datetime, prices as float).
Currency Formatting: Use .replace() to handle and format currency values for analysis.
Validation: Check for any remaining inconsistencies and verify the cleaned data.

#### 6. Feature Engineering
Create New Columns: Calculate the Total Amount for each transaction by multiplying unit_price by quantity and adding this as a new column.
Enhance Dataset: Adding this calculated field will streamline further SQL analysis and aggregation tasks.

#### 7. Load Data into MS SQL Server
Set Up Connections: Connect to MS SQL Server using sqlalchemy and pyodbc, and load the cleaned data into each database.
Verification: Run initial SQL queries to confirm that the data has been loaded accurately.

#### 8. SQL Analysis: Complex Queries and Business Problem Solving
Business Problem-Solving: Write and execute complex SQL queries to answer critical business questions, such as:
Revenue trends across branches and categories.
Identifying best-selling product categories.
Sales performance by time, city, and payment method.
Analyzing peak sales periods and customer buying patterns.
Profit margin analysis by branch and category.
Documentation: Keep clear notes of each query's objective, approach, and results.

#### 10. Project Publishing and Documentation
Documentation: Maintain well-structured documentation of the entire process in Markdown or a Jupyter Notebook.

