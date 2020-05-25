# Movies-ETL

## Challenge Overview 
Using the code done in the module create an automated ETL pipline that can extract data from multiple sources, clean and transform the data automatically, and load new data into PostgreSQL.

## Assumptions that must be made
1. Everything is named the same. This is a necessary assumption because if things are not named the same the code will not be able to run. If the columns or data sets have a different name it is important to use this challenge.py as a templete and replace the names.

2. That psycopg2 is already installed on your system. This was something I had trouble with when trying to connect Pandas to PostgreSQL, but if you go to your terminal and type 'pip install psycopg2' you can run the code with no issue.


3. The third assumption is that there is no column data that need to be additional fixed. In the module we dropped some data that would have been too much trouble to clean up and extract, so we did not use it because it was unnecessary for our analysis. 


4. That the name of the user is "postgres" and that the config file is created in your computer and stores your password as db_password. This is important becasue if it is not the case then you cannot connect to your PostgreSQL server.

5. The final assumption is that all the formating is the same on the columns that we are cleaning up using regular expressions. If they are not then are regular expressions must be changed in order to extract the proper data. 
