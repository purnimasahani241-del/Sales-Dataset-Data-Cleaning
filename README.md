Sales Dataset Data Cleaning Mini Project

Project Overview :

This mini project focuses on cleaning and preprocessing a messy sales dataset using Python, Pandas, NumPy and Jupyter Notebook.

Technologies Used :

Python
Pandas
NumPy
Jupyter Notebook
Dataset Columns
OrderID
CustomerName
City
Product
Quantity
UnitPrice
OrderDate
OrderStatus
CustomerAge
Data Cleaning Tasks Performed
Loaded the CSV dataset using Pandas.
Inspected the dataset using head(), info(), shape() and isnull().
Removed extra spaces from text columns.
Standardized city names and order statuses.
Converted incorrect data types into suitable formats.
Handled missing values using median and Unknown values.
Standardized date formats and handled invalid dates.
Identified and handled outliers using validation rules and IQR method.
Removed duplicate records.
Created a TotalAmount column using Quantity × UnitPrice.
Exported the cleaned dataset into a CSV file.

Final Results :

Original Records: 185
Final Records: 177
Original Columns: 9
Final Columns: 10
Missing Values: 0
Duplicate Records: 0

Project Files :

Sales_Dataset_Data_Cleaning.ipynb – Jupyter Notebook containing the cleaning process.
cleaned_sales_dataset.csv – Final cleaned dataset.
Messy_data.csv – Original dataset.

Conclusion :

The sales dataset was successfully cleaned and prepared for further data analysis using Python and Pandas.
