# Movies-ETL
## Purpose
The purpose of this exercise was to perform ETL on various movie datasets to predict what films would become popular for a streaming service.
## Challenge
Created a function (extract_transform_load) which runs through various datasets to perform extraction, transformation, and loading of the information. In this case, the function extracts data from three files: wikipedia-movies.json, movies_metadata.csv, and ratings.csv. It then performs the transformation, which includes cleaning data from both the Wikipedia and Kaggle datasets. Once the data is cleaned, the Wikipedia and Kaggle Movies datasets are merged into one dataset. Once we clean the ratings dataset, we also add it to our dataframe in a new dataframe. The newly transformed datasets are then loaded into SQL database for further analysis.
