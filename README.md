# European-Bike-sales-data-cleaning-
Big data cleansing using SQL server (all the querries used could be viewed in the Bike Sale Solution.ssmssln file).
The sales dataset of bike stores in 6 developed countries from 2011 to 2016 was collected from Kaggle.com (the original data could be viewed in the Bike sale.csv file).
To start the data cleansing process, the Global Bike Sale database is selected before executing any query. 
Firstly, the primary key which is Order_ID is filtered to find and get rid of duplicated data. 
After that, null data in the profit column were investigated. Since there were only 58 rows of null values in this column (figure 1), the deletion method was adopted to clean these null values (figure 2)  
The Cleaned Bike Sale.csv file was exported after the dataset was cleaned using SQL Server. Then, this cleaned dataset was imported to Tableau for further visualization and analysis. 
