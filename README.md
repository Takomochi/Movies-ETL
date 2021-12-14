# Movies ETL

## Overview of the project
Amazing Prime is a online streaming service company. They needs to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.

Here are the tasks for the project.
1. Write an ETL Function to Read Three Data Files [ETL_function_test.ipynb](https://github.com/Takomochi/Movies-ETL/blob/main/ETL_function_test.ipynb)
2. Extract and Transform the Wikipedia Data [ETL_clean_wiki_movies.ipynb](https://github.com/Takomochi/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb)
3. Extract and Transform the Kaggle data [ETL_clean_kaggle_data.ipynb](https://github.com/Takomochi/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb)
4. Create the Movie Database [ETL_create_database.ipynb](https://github.com/Takomochi/Movies-ETL/blob/main/ETL_create_database.ipynb)

## Resources
- Resources:  [movies_metadata.csv](https://github.com/Takomochi/Movies-ETL/blob/main/Resources/movies_metadata.csv), [wikipedia-movies.json](https://github.com/Takomochi/Movies-ETL/blob/main/Resources/wikipedia-movies.json), ratings.csv
- Software: Python3.7.10, Jupyter Notebook


## Results

Open pgAdmin and check number of rows for each table.<br>

movies table &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;ratings table<br>
<img src="https://github.com/Takomochi/Movies-ETL/blob/main/Resources/movies_query.png" height=200 width=200> <img src="https://github.com/Takomochi/Movies-ETL/blob/main/Resources/ratings_query.png" height=200 width=200>

Each table has the correct number of rows.<br>
We could successfully import those data frames to the database. 
