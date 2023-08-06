# Home_Sales

## Summary

Here I will use SparkSQL to determine key metrics about home sales data. Temporary views will be created, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Details/Process

1. Import the necessary PySpark SQL functions for this assignment.
3. Read the home_sales_revised.csv data into a Spark DataFrame.
4. Create a temporary table called home_sales.
5. Answer the following questions using SparkSQL:
    a.What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    b. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    c. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
    d. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
6. Cache your temporary table home_sales.
7. Check if your temporary table is cached.
8. Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
9. Partition by the "date_built" field on the formatted parquet home sales data.
10. Create a temporary table for the parquet data.
11. Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
12. Uncache the home_sales temporary table.
13. Verify that the home_sales temporary table is uncached using PySpark.

## Sources
Module 22 activities, 
https://sparkbyexamples.com/pyspark/pyspark-sql-with-examples/?expand_article=1, 
https://medium.datadriveninvestor.com/big-data-analytics-with-pyspark-pyspark-on-google-colab-5abe2322221
https://programmingwithmosh.com/tutorials/

## Files
ReadMe.md, Home_Sales_Colab.ipynb (notebook using PySpark in Google Colaboratory)
