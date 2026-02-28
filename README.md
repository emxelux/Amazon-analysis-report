# Amazon-analysis-report
A data analysis project featuring amazon sales data. I used Python for the data cleaning, Excel for the analysis, PowerBI for the Visualizations.
<<<<<<< HEAD
# Data Cleaning Process
=======

Data Cleaning Process
>>>>>>> 57ebd6f (Updated the readme file)
	Removed Duplicated Records
	Standardized Inconstistent Formatting
	Dealt with the missing records in the amount column 
•	Initially, the 'Amount' column contained 7795 missing values.
•	After the first imputation step, which used the median 'Amount' for each 'SKU', the number of missing values was reduced significantly to 44.
•	The subsequent imputation, using the median 'Amount' for each 'Category', successfully filled the remaining 44 missing values.
•	Upon completion of all imputation steps, the 'Amount' column had 0 missing values, confirming its cleanliness.

