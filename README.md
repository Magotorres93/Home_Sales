# Home_Sales

This repository contains a Jupyter Notebook named "Home_Sales_starter_code.ipynb" that will assist you in performing home sales analysis using PySpark. Follow the instructions below to complete the task:

Preliminary Steps
Rename the "Home_Sales_starter_code.ipynb" file to "Home_Sales.ipynb" before starting the tasks.

Import the necessary PySpark SQL functions for this project in the "Home_Sales.ipynb" file.

Read the data from the "home_sales_revised.csv" file provided in the starter code into a Spark DataFrame.

Create a temporary table named "home_sales" with the data from the DataFrame.

Answer the Questions
Use SparkSQL to answer the following questions:

-What is the average price for a four-bedroom house sold for each year? Round your answer to two decimal places.

-What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round your answer to two decimal places.

-What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round your answer to two decimal places.

-What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round your answer to two decimal places.

Data Caching
Cache your temporary table "home_sales" to improve query performance.

Check if your temporary table is cached.

Using the cached data, run the query that filters out the view ratings with an average price greater than or equal to $350,000. Determine the runtime and compare it to the uncached runtime.

Partition Data into Parquet
Partition the home sales data by the "date_built" field and save it in parquet format.

Create a temporary table for the parquet data.

Run the query that filters out the view ratings with an average price greater than or equal to $350,000 on the parquet formatted data. Determine the runtime and compare it to the uncached runtime.

Cache Cleanup
Uncache the "home_sales" temporary table.

Verify that the "home_sales" temporary table is no longer cached using PySpark.

Submission
Download your "Home_Sales.ipynb" file and upload it to your GitHub repository named "Home_Sales".
Good luck with your home sales analysis project! If you have any questions or need further assistance, feel free to reach out.








