# ETL
ETL Process
This project shows the ETL process. 

Step -1: Extracting the Data -
For this project there are three data files. Two files contain the countries and their market cap in USD. Third file contains the exchange rates.
First data files are extracted by using the read_json of pandas and loaded into dataframes. Two files which have the countries and their market cap are appended to a single file.

Step -2: Transforming the Data -
In this step the data is transformations are done.
The market cap values of all the countries are conversted from USD to GBP. The column name has been changed and the values are rounded to 3 decimals.

Step -3: Loading the Data -
In this step, the data has been loaded into csv file. The csv file automatically gets downloaded in the current working directory.

Logs -
There is a function for logging all the steps, so that it would be easy for the user to track the ETL processes. This function shows the time and the step that has been executed at that particular time.
