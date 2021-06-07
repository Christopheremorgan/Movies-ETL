# Movies-ETL

## Overview/Purpose
The code in the repository is an ETL project to provide clean movie data for a hackathon event.   It has been built in a way to automate the pull, clean and load for future hackathons.

## Deliverables

[Deliverable 1: ETL Function Test](https://github.com/Christopheremorgan/Movies-ETL/blob/main/ETL_function_test.ipynb) 

[Deliverable 2: Clean Wiki Data](https://github.com/Christopheremorgan/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb) 

[Deliverable 3: Clean Kaggle & Ratings Data](https://github.com/Christopheremorgan/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb) 

[Deliverable 4: Create Database](https://github.com/Christopheremorgan/Movies-ETL/blob/main/ETL_create_database.ipynb) 
Note: Deliverable 4 includes all code to extract, clean and load into Postgres.  The movie dbase is automatically replaced, but if rerunning code need to drop the ratings dbase in Postgres before running.


![Movie Table Select Count Query](https://github.com/Christopheremorgan/Movies-ETL/blob/main/Resources/movies_query.png)

![Ratings Table Select Count Query](https://github.com/Christopheremorgan/Movies-ETL/blob/main/Resources/ratings_query.png)

## Data Files
[Kaggle Movies Metadata](https://github.com/Christopheremorgan/Movies-ETL/blob/main/Resources/movies_metadata.csv.zip) 

[Wikipedia Movies JSON File](https://github.com/Christopheremorgan/Movies-ETL/blob/main/Resources/wikipedia-movies.json) 

Ratings from MovieLens not included in the repository
