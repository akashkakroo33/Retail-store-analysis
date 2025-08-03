# Retail Store Data Analysis using Pandas and SQL

## Project Objective
The objective of this project is to conduct a Retail Store Analysis for the year 2022 and 2023. The goal is to help the store owner gain valuable insights into customer behavior, sales trends, and product performance. By analyzing annual sales data, the owner can make informed decisions to increase revenue, improve customer satisfaction, and drive business growth in 2022 and 2023.


## Dataset used
- [Dataset](https://www.kaggle.com/datasets/ankitbansal06/retail-orders)

## Questions
- Find top 10 highest reveue generating products
- Find top 5 highest selling products in each region
- Find month over month growth comparison for 2022 and 2023 sales eg : jan 2022 vs jan 2023
- Which sub category had highest growth by profit in 2023 compare to 2022
- For each category which month had highest sales

## Process
- Imported the Kaggle retail dataset into the Jupyter Notebook for analysis.
- Explored the dataset by checking all unique values to understand data distribution.
- Standardized missing values by converting all entries like 'Not Available' and 'Unknown' to null using the na_values
- Cleaned and transformed column names:
- Converted all column names to lowercase.
- Replaced spaces with underscores for better consistency in analysis.
- Created new derived columns for:
  - discount
  - sale_price
  - profit
- Converted the order_date column from object type to datetime format for time-based analysis.
- Loaded the cleaned and enriched data into SQL Server using the append option for further querying and dashboarding.


  

