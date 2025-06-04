-Data Extraction
-The following SQL query was used to extract the necessary columns from BigQuery:
SELECT 
  store_location, 
  transaction_qty,
  product_category, 
  product_type
FROM `silent-kite-449818-c3.Brainwave_task_1.coffee shop sales`
GROUP BY 
  store_location, 
  transaction_qty,
  product_category, 
  product_type
ORDER BY 
  transaction_qty DESC;
