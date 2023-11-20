
# RFM Analysis with SQL

# Project Objective and Introduction

In this project, I explored a sales dataset and generated various analytics and insights from customers' past purchase behavior. I also go from analyzing sales revenue to creating a customer segmentation analysis using the RFM technique.

Here are the SQL skills I utilized in this project:

- Importing a file into SQL Server Database
- SQL Aggregate Functions
- SQL Window Functions
- SQL Sub Query
- Common Table Expressions (CTEs)

# Data Source

The dataset is the Sales Data Sample from Kaggle.

# Create a Database and Importation of Dataset

I created a dataset [dbo] using my SQL command promt and i imported my [sales_data_sample] using MySQL Table Data Import Wizard.

# Exploratory Data Analysis

In order to comprehend the dataset I’m handling, I engage in data exploration of the dataset and this involves:

1.	Inspecting the dataset using ‘Select * from [sales_data_sample]’
2.	Checking for distinct values in some columns of the dataset to know the Unique values in the columns.

# Data Analysis

Using basic SQL queries, SUB QUERY, CTEs, AGGREGATE, and WINDOW functions I performed the following analysis. First, I started by grouping sales by product line then;

1.	Analyzing the best month for sales in a specific year and how much was earned that month.
2.	Analyzing the product that was sold in the best Month.
3.	Using RFM, i also analysed the best customer
4.	Analyzed what product are most often sold together.
5.	Analyzed what city has the highest number of sales in a specific country
6.	Analyed what is the best product in United States?


In summary, the analysis of the 'sales_dataset_sample' dataset via SQL revealed several key insights:

- Classic Cars emerged as the top-selling product line, followed by Vintage Cars and then Other Cars.

- The year 2024 recorded the highest sales, closely followed by 2023 in the full calendar year. However, sales were notably lower in 2025 due to the store's operation for only five months.

- When examining specific years, like 2023, November stood out as the month with the highest sales. The SQL query can be customized to identify the best-selling month for each year.

