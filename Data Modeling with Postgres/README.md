## 1. Introduction
   Sparkify is a music startup that provides music streaming services. Their analytics team wants to understand what songs users are listening to, but they don't have an easy way to query and analyze the data. The project builds the database from json metadata and the ETL pipeline for analysis.

## 2. Database schema design and ETL process
   Dimension tables: Users, Songs, Artists, Time
   Fact table: Songplays
   The ETL process includes processing json metadata files, and insert the data into database.

## 3. Files in repository
   data folder: song data and log data files
   create_tables.py: functions and commands to create tables from the sql queries
   etl.ipynb: an ipython notebook that develops the ETL process for each table
   etl.py: the script that contains the etl pipeline
   sql_queries.py: SQL queries that create tables and insert data into tables
   test.ipynb: an ipython notebook that contains SQL queries to test if the tables are correctly created and data are correctly inserted into the table

## 4. How to run the python scripts
   In the terminal, run create_tables.py first to create the database. Then run test.ipynb to see if tables are correctly created. After finishing etl.ipynb and etl.py, run etl.py in the termianl to streamline the etl process. 

