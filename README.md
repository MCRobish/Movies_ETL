# Movies_ETL

## Description: 
The purpose of the files in this repository was to take data from Wikipedia and from Kaggle (movie database) and clean the data up to reduce the amount of columns. Several columns were also reformatted to have consistent datatypes. These sources were then merged into two large dataframes, and loaded into an SQL database. 

**Resource Folder:** Contains the raw data as well as screenshots of the query results once the tables were loaded into SQL 
**ETL_create_database.ipynb:** contains the functions created in the ETL_clean_wiki_movies and the ETL_clean_kaggle_data, as well as the time elapsed to load all of the transformed dataframes into SQL. 
