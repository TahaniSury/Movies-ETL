# Movies-ETL

## Purpose
The goal of this analysis is to create automated pipeline that extracts, transform and loads data. This analysis consists of four parts, where each step is building up from beginning of extracting data and function testing, through transformation and cleaning process to its final step connect and load to the database.The ETL process is broken down into four jupyter notebook files:

### ETL_function_test.ipynb

Data is extracted from the website in JSON and CSV formats then transformed into Pandas data frames

### ETL_clean_wiki_movies.ipynb

Function clean_movie combines scattered data of alternative languages into one column alt_titles.

### ETL_clean_kaggle_data.ipynb

Function (three_function) extract_transform_load gets new tasks for cleaning Kaggle data 

### ETL_create_database.ipynb

The function in its final step connects to the database by sqlalchemy library and to_sql method.
Complete ETL process can be executed with a single function (three_function) extract_transform_load call 
