# Movies-ETL

## Purpose of the analysis

This project aims to create a Movies Database from three different sources: Wikipedia Data, Kaggle Metadata, and the MovieLens rating data; through an ETL process. 

## Summary of the process

To accomplish this goal, I followed the process below:
- Write an ETL function to read the files and create three separate DataFrames using Python, Pandas, and the ETL process.
- Extract and transform the Wikipedia data to merge it with the Kaggle metadata. 
- Extract and transform the Kaggle metadata and MovieLens rating data to convert it into separate DataFrames. Both procedures were performed by using python, Pandas, and an ETL process. The outcome of this process was the creation of a Movies dataframe.
- To finish, I used PostgreSQL to add the Movies DataFrame and MovieLens rating data to a SQL database.
