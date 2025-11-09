# AnalyzingAndFormattingSalesData_SQL

In this project, we will work with data from a hypothetical Super Store to challenge and enhance our SQL skills in data cleaning. This project will engage us in identifying top categories based on the highest profit margins and detecting missing values, utilizing our comprehensive knowledge of SQL concepts.

Let's dive into the world of SQL and work our magic to clean and analyze data from our hypothetical Super Store.

1. Find the top 5 products from each category based on highest total sales. The output should be sorted by category in ascending order and by sales in descending order within each category, i.e. within each category product with highest margin should sit on the top. Save the query as top_five_products_each_category, containing the following columns:
  category
  product_name
  product_total_sales (rounded to two decimal places)
  product_total_profit (rounded to two decimal places)
  product_rank

2. Calculate the quantity for orders with missing values in the quantity column by determining the unit price for each product_id using available order data, considering relevant pricing factors such as discount, market, or region. Then, use this unit price to estimate the missing quantity values. The calculated values should be stored in the calculated_quantity column. Save query output as impute_missing_values, containing the following columns:
  product_id
  discount
  market
  region
  sales
  quantity
  calculated_quantity (rounded to zero decimal places)
