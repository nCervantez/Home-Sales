# Home Sales PySpark Analysis

## Overview of the Analysis:
The purpose of this project is to use PySpark to conduct SQL queries on a dataset, using cached tables, as well as parquet data, and determine which is faster. In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

### SparkSQL:

Answer the following questions using SparkSQL:

- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

- What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

- What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

- What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

### Parquet

We will convert the data into Parquet format, and partition the data on the 'date_built' column and perform the fourth query to determine runtime differences between Parquet and cached tables.

### Tools Used

- Jupyter Notebook

- Python

- PySpark

- Findspark
