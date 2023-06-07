What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
Answer = 
+----+-------------+
|year|average_price|
+----+-------------+
|2022|    296363.88|
|2019|     300263.7|
|2020|    298353.78|
|2021|    301819.44|
+----+-------------+

What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
Answer = 
+----------+-------------+
|date_built|average_price|
+----------+-------------+
|      2010|    292859.62|
|      2011|    291117.47|
|      2012|    293683.19|
|      2013|    295962.27|
|      2014|    290852.27|
|      2015|     288770.3|
|      2016|    290555.07|
|      2017|    292676.79|
+----------+-------------+

What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
Answer = 
+----------+-------------+
|date_built|average_price|
+----------+-------------+
|      2010|    285010.22|
|      2011|    276553.81|
|      2012|    307539.97|
|      2013|    303676.79|
|      2014|    298264.72|
|      2015|    297609.97|
|      2016|     293965.1|
|      2017|    280317.58|
+----------+-------------+

What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
Answer = 
+----+-------------+
|view|average_price|
+----+-------------+
|   0|    403848.51|
|   1|    401044.25|
|   2|    397389.25|
|   3|     398867.6|
|   4|    399631.89|
|   5|    401471.82|
|   6|    395655.38|
|   7|    403005.77|
|   8|    398592.71|
|   9|    401393.34|
|  10|    401868.43|
|  11|    399548.12|
|  12|    401501.32|
|  13|    398917.98|
|  14|    398570.03|
|  15|     404673.3|
|  16|    399586.53|
|  17|    398474.49|
|  18|    399332.91|
|  19|    398953.17|
+----+-------------+
only showing top 20 rows

--- 0.13956189155578613 seconds ---

Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
Answer =
+----+-------------+
|view|average_price|
+----+-------------+
|   0|    403848.51|
|   1|    401044.25|
|   2|    397389.25|
|   3|     398867.6|
|   4|    399631.89|
|   5|    401471.82|
|   6|    395655.38|
|   7|    403005.77|
|   8|    398592.71|
|   9|    401393.34|
|  10|    401868.43|
|  11|    399548.12|
|  12|    401501.32|
|  13|    398917.98|
|  14|    398570.03|
|  15|     404673.3|
|  16|    399586.53|
|  17|    398474.49|
|  18|    399332.91|
|  19|    398953.17|
+----+-------------+
only showing top 20 rows

--- 0.11781787872314453 seconds ---

Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
Answer =
+----+-------------+
|view|average_price|
+----+-------------+
|   0|    403848.51|
|   1|    401044.25|
|   2|    397389.25|
|   3|     398867.6|
|   4|    399631.89|
|   5|    401471.82|
|   6|    395655.38|
|   7|    403005.77|
|   8|    398592.71|
|   9|    401393.34|
|  10|    401868.43|
|  11|    399548.12|
|  12|    401501.32|
|  13|    398917.98|
|  14|    398570.03|
|  15|     404673.3|
|  16|    399586.53|
|  17|    398474.49|
|  18|    399332.91|
|  19|    398953.17|
+----+-------------+
only showing top 20 rows

--- 0.2798628807067871 seconds ---