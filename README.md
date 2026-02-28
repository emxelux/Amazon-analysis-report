# Amazon-analysis-report
A data analysis project featuring amazon sales data. I used Python for the data cleaning, Excel for the analysis, PowerBI for the Visualizations.
Original Dataset file: https://1drv.ms/x/c/f5058b052baeb8e6/IQC-KKeV45lDRqA2uVULRyrdARH8xPoZ9Hl3uWbpClxAq18?e=mtG4Bt
Cleaned Dataset file: https://1drv.ms/x/c/f5058b052baeb8e6/IQBfdC99MAAvS6IbW57g3BYTAWQkMxx5nIP8pZevEfsf9nc?e=hEuJhT
<<<<<<< HEAD
# Data Cleaning Process
	Removed Duplicated Records
	Standardized Inconstistent Formatting
	Dealt with the missing records in the amount column 
    •	Initially, the 'Amount' column contained 7795 missing values.
    •	After the first imputation step, which used the median 'Amount' for each 'SKU', the number of missing values was reduced significantly to 44.
    •	The subsequent imputation, using the median 'Amount' for each 'Category', successfully filled the remaining 44 missing values.
    •	Upon completion of all imputation steps, the 'Amount' column had 0 missing values, confirming its cleanliness.

