# Movies-ETL
Use ETL to collect, transform, and load data into existing tables using a PostgreSQL database

## Overview
To start, we extracted data using a function to create three separate dataframes. T

## Results
To start, we extracted data using a function to create three separate dataframes. TOnce we had the three dataframes completed we needed to transform the data in order to more accurately represent the data we wanted to show. Finally we needed to merge the dataframes into the Movies_DF which we then loaded into a PostgreSQL dataframe.

![Movies DF](https://github.com/sbull32/Movies_ETL/blob/main/Resources/.png)

Once we had completed uploading the dataframe to PostgreSQL we confirmed that we had properly imported the data by querying the total count of ratings and movie titles in our respective tables. 

![Ratings Query](https://github.com/sbull32/Movies_ETL/blob/main/Resources/ratings_query.png)

![Movies Query](https://github.com/sbull32/Movies_ETL/blob/main/Resources/movies_query.png)

## Summary
