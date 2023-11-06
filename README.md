# Home_Sales
Module 22

## Description:
Using the knowledge of SparkSQL, I have determined key metrics about home sales data. I used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached. 
 ## Installations
 I used SparkSession from pyspark.sql, SparkFiles from pyspark and time.

 ## Other Instructions:
The indepth queries and codes can be found in the Home_Sales jupyter notebook. Each Code has its own explanation at the top.

 ## Contributing
All the problems are solved with the help of the activities.

## Observation
The normal query took 0.78 seconds to run, the query using the cached data took 0.58 seconds to run which is the fastest and lastly the query using the parquet DataFrame took the longest with 1.53 seconds.
