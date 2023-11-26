# Market-Basket-Analysis-Using-Apriori-Algorithm


Project Description

This is the first project in FLIT apprenticeship projectized learning. The dataset used is grocery data from a retail company. It contains customers' transactions. It has 38765 rows and 3 columns. The task is to perform a market basket analysis to uncover customer purchasing behaviors. By identifying which products tend to be bought together, the company can make informed decisions to improve sales and customer satisfaction.

 

Steps

Data loading and inspection:

· Import the necessary libraries and read the datasets.

· Check the shape of the dataset and the datatype of the columns.

· Check for missing and duplicated values.

 

Data Cleaning

· Remove duplicates

· Convert the date column to DateTime.

 

Exploratory Data Analysis

· Check the most frequently bought items.

· Show the top 15 products frequently sold in a chart.



Data Preparation

Create a data frame containing each unique combination of member and date and a concatenated string of items associated with each combination.
Create a numpy array of the item descriptions.
Use list comprehension to convert the numpy array of item descriptions into a list of lists, where each list contains a different set of items.
Use a transaction encoder to get frequent item sets and then store them in a data frame.
Apriori Algorithms

Apply the apriori algorithms.
Create a column with the length of the itemsets.
Apply the association rule based on a minimum threshold of 0.02.
 

 

Insights

Use lift and confidence for the evaluation of the association rule.

Conclusion
There is a positive correlation if the lift is greater than one, and a negative correlation if the lift is less than one.


