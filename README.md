# Home_Sales
 
## Overview
In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Results
The original query ran in 0.24687 seconds
The cached query ran in 0.14060 seconds
The partitioned query ran in 0.22174 seconds

## Analysis
Caching the data was the most effective method. Partitioning likely would have been more effective had I partitioned on something other than "date_built" which was not used in the query. 
