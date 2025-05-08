# certificate-structure-
Aim:
Creating certificate structure and storing the records in Database. 

Requirement List:
1.Code language ------> Python version(3.12.7).
2.libraries     ------> Pandas version(2.2.2).
3.Input File    ------> **********.

Steps:
* Import the required libraries.
* Reading the Excel File, Load data from the Excel file into a Data Frame called df.
* Display the first 5 rows to inspect the structure and sample data.
* Remove all whitespace (including invisible ones) from column names using Python's regular expressions (regex) module.
* (OR) another Alternative Method of removing whitespace using pandas string method.
* Now verify that all leading/trailing whitespace is removed.check the value Should return 0.
* Upload to MySQL database using SQLAlchemy.
  ---> if_exists='replace' means it will overwrite the table if it already exists.
  ---> index=False ensures index is not added as a column.
* Sets up a connection to a MySQL database using SQLAlchemy.
* Database details must be updated with actual credentials.
* Check and display column names & number of rows and columns for confirmation. 
* Now finally upload to MySQL.
