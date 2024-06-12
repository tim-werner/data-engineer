# Task
The objective of this task is to design and implement a solution to process data files.

There are 2 data files [dataset_names.csv](/dataset_names.csv) and [dataset_price.csv](/dataset_price.csv), design a solution to process these files and push them into a duckdb database. The expected output of the processing task is a duckdb database including a table containing at least **first_name**, **last_name**, **price** and **above_100** columns.

Please provide the code via email to explain your solution.

Processing tasks:
- Split the name field into **first_name**, and **last_name**
- Round the **price** fields to two decimal places
- Create a new field named **above_100**, which is true if the price is strictly greater than 100
- create a table in duckdb that contains **first_name**, **last_name**, **price** and **above_100** 

Note: 
   
- *you might install duckdb via ```pip install duckdb```*
- *provide a documentation that explains how to run it*