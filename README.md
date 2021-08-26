# Movies-ETL

## Overview 

Perform ETL and data cleaning/loading on several movie datasets to predict popular films for a streaming service.

Created an ETL (Extract, Transform, and Load) of movie and wikipedia data. This process entails (E)xtracting Wikipeda, IMDB (kaggle dataset) movie metadata and MovieLens rating metadata. (T)ransform the data in to a clean, usable and uniform. Addressing all the descripencies between the mulitple metadata sets, removing null values and standardizing the different viewing formats. Then the dataset all merged together into a single DataFrame / dataset to be exported into a database. (L)oad the cleaned data set into a SQL database in order to run queries for desired outputs.

- Create an ETL pipeline from raw data to a SQL database.
- Extract data from disparate sources using Python.
- Clean and transform data using Pandas.
- Use regular expressions to parse data and to transform text into numbers.
- Load data with PostgreSQL.


### Software

Jupyter Notebook \
VS Code \
PostgreSQL \
pgAdmin \
Pandas - Python \
SQL 

### Data Sources

- Wikipedia Metadata: wikipedia-movies.json [Wiki-Movies](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_8/wikipedia-movies.json)

- Kaggle Data movies_metadata.csv, ratings.csv [The Movie Database](https://www.themoviedb.org/)



