# working_with_ETL

## Overview

The purpose of this challenge was to depict the use of functions to streamline the amount of code needed to extract transform and load wikipedia movie data with kaggle and ratings. Each Deliverable expands on the functions created in the previous one to help simplify and also make sure that each file is done correctly before transforming the next file.

## Results

The functions that were created `clean_movie`, `parse_dollar`, and `extract_transform_load` were nested within each other to run transform the data. In deliverable 4 the cleaned data was then put into a SQL database. The data was then queried to show that all lines of movie and ratings tables were uploaded as seen below. The functions that were created could be used to keep these created databases up to date with the updating of the original .csv and .json files.

Movie Count
![Movies_data](https://github.com/drewabramo12/working_with_ETL/blob/main/Resources/movies_query.PNG)

Rating Count
![Rating_data](https://github.com/drewabramo12/working_with_ETL/blob/main/Resources/ratings_query.PNG)