# Home_Sales# Home_Sales

 April 2024 | Dotan Barak

### Table of Contents: 

1. [Summary](#Summary)
2. [Contents](#Contents)
3. [Questions](#Questions)
4. [References](#References)

### Summary

The purpose of this project was to utilize Spark to read in a home sales data set, create temporary views and tables, and to execute SQL queries answer key questions with the data.

### Contents

-   Home_Sales_starter_code.ipynb
-   README.md


This repository includes the Jupyter Notebook in which the data set was analyzed. The .CSV and partitioned Parquet files have been omitted from the repository for size considerations.

### Questions

#### 1. What is the average price for a four-bedroom house sold for each year?

Average sale price per year for homes with 4 beds:
+----+---------+
|year|avg_price|
+----+---------+
|2022|296363.88|
|2021|301819.44|
|2020|298353.78|
|2019| 300263.7|
+----+---------+

#### 2. What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms?

+----------+---------+
|year_built|avg_price|
+----------+---------+
|      2017|292676.79|
|      2016|290555.07|
|      2015| 288770.3|
|      2014|290852.27|
|      2013|295962.27|
|      2012|293683.19|
|      2011|291117.47|
|      2010|292859.62|
+----------+---------+
#### 3. What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?

+----------+---------+
|built_year|avg_price|
+----------+---------+
|      2017|280317.58|
|      2016| 293965.1|
|      2015|297609.97|
|      2014|298264.72|
|      2013|303676.79|
|      2012|307539.97|
|      2011|276553.81|
|      2010|285010.22|
+----------+---------+

#### 4. What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000?

+-----------+--------------+
|view_rating|avg_home_price|
+-----------+--------------+
|        100|     1026669.5|
|         99|    1061201.42|
|         98|    1053739.33|
|         97|    1129040.15|
|         96|    1017815.92|
|         95|     1054325.6|
|         94|     1033536.2|
|         93|    1026006.06|
|         92|     970402.55|
|         91|    1137372.73|
|         90|    1062654.16|
|         89|    1107839.15|
|         88|    1031719.35|
|         87|     1072285.2|
|         86|    1070444.25|
|         85|    1056336.74|
|         84|    1117233.13|
|         83|    1033965.93|
|         82|     1063498.0|
|         81|    1053472.79|
+-----------+--------------+

## References

- Data Source: Dataset provided by edX Boot Camps LLC for educational purposes.
- SparkSQL documentation: https://spark.apache.org/docs/latest/sql-getting-started.html
- No external code or outside collaboration used beyond the instructional materials.
