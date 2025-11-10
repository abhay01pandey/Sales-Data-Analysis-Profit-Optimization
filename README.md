# Sales-Data-Analysis-Profit-Optimization
This project performs a data analysis on retail order transactions to uncover insights related to sales performance, discounts, and profitability across different product categories and regions.

The main objective is to clean and transform the dataset, calculate new business metrics, and prepare the data for further reporting or visualization.

# Dataset & Tools Used
Dataset:

orders.csv — retail dataset containing details about customer orders, pricing, discounts, and profits.

Tools & Libraries:

Jupyter Notebook

pandas – data manipulation and cleaning

numpy – numeric computation

# Workflow
Load Data: Imported dataset using pandas.read_csv() and displayed the first few records for inspection.

Handle Missing Values: Replaced invalid values such as 'Not Available' and 'unknown' with NaN.

Rename Columns: Standardized column names to lowercase and snake_case format.

Created new columns:

discount = list_price * discount_percent / 100

sale_price = list_price - discount

profit = sale_price - cost_price

Data Type Conversion: Converted order_date column to proper datetime format.

Optimization: Dropped unnecessary columns (list_price, cost_price, discount_percent).

# Insights
Generated new business metrics: discount amount, sale price, and profit.

Identified the impact of discount percentage on overall profit margin.

Cleaned and standardized all Ship Mode entries, removing invalid values.
