<h1 align="center">DU - University of Denver<br/>
Data Analysis & Visualization Bootcamp<br/></h1>

--------------------------------

<h2 align="center">Big Data and PySpark<br/>
(Using Google Colab)
Module 22 Challenge
<br/>
By Laura Vara</h2><br/>


In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.
<br/>
<br/>
**Note:** While there are two Jupyter Notebook formated files and both have the same code, the 'Home_Sales_colab.ipynb' was the were I ran the code via Google Colab. Therefore it's the only one of these two files that has the output to the queries.


![GitReadMe_TxtImage](https://github.com/vara-co/Home_Sales/assets/152572519/037795f3-fc92-49a8-82e1-8b43b97dd047)

---------------------------------
INDEX
---------------------------------
1. Content of the repository
2. Instructions for the Project
3. References

---------------------------------
Content of the repository
---------------------------------
- Home_Sales.ipynb
- Home_Sales_colab.ipynb <-- This is the Jupyter Notebook that I actually worked on via Google Colab, thus it has the outputs to each cell of code.

----------------------------------
Instructions
----------------------------------
1. Rename the **Home_Sales_starter_code.ipynb** file as **Home_Sales.ipynb**
2. Import the necessary PySpark SQL functions for this assignment.
3. Read the **home_sales_revised.csv** data in the starter code into a Spark DataFrame.
4. Create a temporary table called **home_sales**
5. Answer the following questions using SparkSQL:
    * What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places
    * What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    * What is the average price of a home for each year the home was built, that has three betrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
    * What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for thi squery, and round off your naswer to two decimal places.
6. Cache your temporary table **home_sales**
7. Check if your temporary table is cached.
8. Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
9. Partition by the "date_built" field on the formatted parquet home sales data.
10. Create a temporary table for the parquet data.
11. Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
12. Uncache the **home_sales** temporary table
13. Verify that the **home_sales** temporary table is uncached using PySpark.
14. Download your **Home_sales.ipynb** file and upload it to your "Home_Sales" GitHub repository.
     * **(NOTE: I worked on the colab version due to the packages installed and the size of the data. Therefore this is the file with the outputs).**


------------------------------------
References
------------------------------------
Everything included in this project was covered in class. Regardless, these two resources were used to complete the challenge.

- Number Padding in PySpark Dataframes: https://stackoverflow.com/questions/45400829/padding-in-a-pyspark-dataframe
