# Large-Dataset-For-MySQL
Large dataset (insert query) mainly for MySQL, customizable for any other Database platform.

# File Descriptions :
  * original_dataset.csv : Collected from https://www.kaggle.com/carrie1/ecommerce-data
  * preprocessed_dataset.csv : Preprocessed data for SQL Environment. You can write your own code to generate a large "Insert Query" from this file, based on your Database Platform.
  * sqlQueries.txt : Generated large "Insert Query" for MySQL Database.
  * table_DDL.txt : In case you need a readymade table to insert the data, for MySQL.

# Data Descriptions:
  * Total data count: 5,41,909
  * Total column count: 9
  * Dataset based on: E-Commerce transactions

Note :
  * Column named CustomerID had some empty values, replaced with -1. Assume -1 means customer isn't a registered customer.
