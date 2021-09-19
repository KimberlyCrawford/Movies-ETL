# Movies_ETL

# Overview
Creating an ETL (Extract, Transform, and Load) pipeline from raw data to a SQL database. 

## Purpose

Amazing Prime Video performed ETL on several movie datasets to predict popular films for their streaming service. Data was gathered from both Wikipedia and Kaggle, combined and saved into a SQL database. Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.
 
# Resources
wikipedia-movies.json
movies_metadata.csv
ratings.csv

-- JSON library was used to extract the Wikipedia data.
-- Pandas library was used to create DataFrames.
-- NumPy library was used for converting data types.
-- Jupyter Notebook was used to explore the data. 
-- Code was copied to a Python script.

NOTE: The read_json method that comes built into the Pandas library only works well for data that is already clean—for example, when the JSON data has every field filled in every time it is returned. We call data like this "flat." Most data you'll work with in real life won't come to you in a flat format. One great thing about the JSON format is it's really flexible, and it can handle raw, messy data. But if you try to read raw, messy JSON data directly into a DataFrame, the DataFrame will be a mess too. It's very difficult to find and fix corrupted data in messy DataFrames, and it's also difficult to consolidate columns without headaches. As you may have guessed, the type of data we get from doing a scrape of Wikipedia is pretty messy, so it's easier to load the raw JSON as a list of dictionaries before converting it to a DataFrame.

# Challenge Deliverables

## Deliverable 1: 
An ETL Function was written to read three data files and three separate dataframes were created.
See ETL_function_test file (https://github.com/KimberlyCrawford/Movies_ETL/blob/main/ETL_function_test.ipynb) for code.

## Deliverable 2: 
The Wikipedia Data was extracted and transformed.
See ETL_clean_wiki_movies file (https://github.com/KimberlyCrawford/Movies_ETL/blob/main/ETL_clean_wiki_movies.ipynb) for code.

## Deliverable 3: 
The Kaggle data was extracted and transformed.
See ETL_clean_kaggle_data file for code.

## Deliverable 4: 
The Movie Database was created.
See ???
