# Movies-ETL

This project is to create an automated pipeline that takes in new data, transforms, and loads in an existing movies table.  The data comes from three sources: Wikipedia data, Kaggle metadata, and MovieLens rating data.  The data will be loaded into a PostgreSQL databas.



## Overview
Extract, Transform, and Load three data files by a single function and be able to massage data through transformation and create dataframes for loading into a movies database.

#Resources
-Jupyter Notebook
-SqlAlchemy
-PostgreSQL
-Pandas Library
-NumPy Library
-wikipedia-movies.json (Wikipedia)
-movies_metadata.csv (Kaggle)
-ratings.csv (MovieLens)

# Write an ETL function to read in three files
-Load and extract the Wikipedia data
-Extract the Kaggle data

## Extract and Transform the Wikipedia Data
-Clean and filder data with list comprehensions
-Create the clean movie function
-Remove the duplicates with regular expresssions
-Remove columns with null values
-Drop null values and convert data to string values.
-Clean the box office data
-Clean the budget data, the release date, and running time

## Extract and Transform the Kaggle Data
-Clean the budget data, the release date, and the running time
-Clean the Kaggle data
-Merge Wikipedia and Kaggle DataFrames
-Transform and merge the ratings data


## Create the Movie Database
-Create and connect to the database, then import data
![Loading of movie dataframe into PostgreSQL](https://github.com/JoePedroza/Movies-ETL/blob/main/Resources/movies_query.png)
![Loading of ratings dataframe into PostgreSQL](https://github.com/JoePedroza/Movies-ETL/blob/main/Resources/ratings_query.png)

