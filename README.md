# Movies_ETL

# Overview
Creating an ETL (Extract, Transform, and Load) pipeline from raw data to a SQL database. 

## Purpose
Amazing Prime Video performed ETL on several movie datasets to predict popular films for their streaming service. Data was gathered from both Wikipedia and Kaggle, combined and saved into a SQL database. Amazing Prime loved the dataset and wanted to keep it updated on a daily basis. 

Challenge: An automated pipeline was created to take in new data, perform appropriate transformations, and load the data into existing tables. The code was refactored to create one function that took in three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data; the ETL process was performed by adding the data to a PostgreSQL database.
 
# Resources
- wikipedia-movies.json
- movies_metadata.csv
- ratings.csv

## Software:
- JSON library was used to extract the Wikipedia data.
- Pandas library was used to create DataFrames.
- NumPy library was used for converting data types.
- Jupyter Notebook was used to explore the data. 
- Code was copied to a Python script.

# Challenge Deliverables

## Deliverable 1: 
An ETL Function was written to read three data files and three separate dataframes were created.
See ETL_function_test file (https://github.com/KimberlyCrawford/Movies_ETL/blob/main/ETL_function_test.ipynb) for code.

![Three_arguments_function.png](https://github.com/KimberlyCrawford/Movies_ETL/blob/main/Three_arguments_function.png)

![Wiki_movies_df.png](https://github.com/KimberlyCrawford/Movies_ETL/blob/main/Wiki_movies_df.png)

![kaggle_metadata.png](https://github.com/KimberlyCrawford/Movies_ETL/blob/main/kaggle_metadata.png)

![ratings.png](https://github.com/KimberlyCrawford/Movies_ETL/blob/main/ratings.png)

## Deliverable 2: 
The Wikipedia Data was extracted and transformed.
See ETL_clean_wiki_movies file (https://github.com/KimberlyCrawford/Movies_ETL/blob/main/ETL_clean_wiki_movies.ipynb) for code.

![Cleaned_wiki_movies_df.png](https://github.com/KimberlyCrawford/Movies_ETL/blob/main/Cleaned_wiki_movies_df.png)

## Deliverable 3: 
The Kaggle data was extracted and transformed.
See ETL_clean_kaggle_data file (https://github.com/KimberlyCrawford/Movies_ETL/blob/main/Cleaned_kaggle_metadata.png) for code.

![Cleaned_kaggle_metadata.png](https://github.com/KimberlyCrawford/Movies_ETL/blob/main/Cleaned_kaggle_metadata.png)

## Deliverable 4: 
The Movie Database was created.
See ???
