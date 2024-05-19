# Business Tasks
## Tasks Performed on the Dataset:
Initially, I performed data cleaning on the dataset, dropping irrelevant columns and generating useful business insights. 

Given below is the step-by-step analysis that has been performed in Employee_payroll data.
1. Removing the **'$'** and **‘,’** signs from the **'Base Pay'** column and changing the column's data type to float.

2. Creating a column **'Fiscal Year'** in which we will get the **'Fiscal Year'** from the **'Fiscal Period'** column.

3. Removing the columns **‘Middle Init’, ’Office’, ’Job Code’, and ‘Position ID’ from the DataFrame.**

4. Getting the count of unique values for the columns **'Fiscal Year'**, **' Office Name'**, **'Job Title'**, and **'Bureau'**

7. Checking How many Job Titles contain **'Service'** in it?

8. Printing the Highest **'Base Pay'** of every **'Office Name'**.

9. Creating a Dataframe having **'Original Hire Date'** as its index and  **'Job Title'** and **'Base pay'** are columns

10. Finding the average **'Base pay'** of every **'Fiscal Year’**.

11. Creating 3 DataFrames **'df_2016'**, **'df_2017',** and **'df_2018'** where each dataframe will contain data only from those **'Fiscal Year’**.

12. Getting all the details where **'Job Title'** is **'Operating Engineer II'** and the **'Base Pay'** is less than 29000 and greater than 25000

13. Concatinating the above 3 Dataframes created  **'df_2016'**, **'df_2017',** and **'df_2018'**, to create a new DataFrame.

14. Getting all the details of Employees whose **' Base Pay'** is the minimum or **'Base Pay'** is the maximum

1. For each ‘**Office Name**’ and ‘**Job Title’**  finding the first and second highest  **'Base Pay'**  salary.
