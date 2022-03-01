# Movies-ETL
Use ETL to collect, transform, and load data into existing tables using a PostgreSQL database

## Overview

We were tasked with taking movie data in from 3 different sources including Kaggle, Wikipedia, and MovieLens and to create a comprehensive DataFrame which included relevant information from each. Once the DataFrame was completed after cleaning and removing excess information, we uploaded it into a SQL database using PostgreSQL.

## Results

To start, we extracted data using a function to create three separate dataframes. TOnce we had the three dataframes completed we needed to transform the data in order to more accurately represent the data we wanted to show. Finally we needed to merge the dataframes into the Movies_DF which we then loaded into a PostgreSQL dataframe.

![Movies DF](https://github.com/sbull32/Movies_ETL/blob/main/Resources/db_columns.png)

Once we had completed uploading the dataframe to PostgreSQL we confirmed that we had properly imported the data by querying the total count of ratings and movie titles in our respective tables. 

![Ratings Query](https://github.com/sbull32/Movies_ETL/blob/main/Resources/ratings_query.png)

![Movies Query](https://github.com/sbull32/Movies_ETL/blob/main/Resources/movies_query.png)

## Summary

Overall this project used numerous techniques to help transform our data once the movies data had been extracted from the original sources. This includes renaming columns, merging dataframes, removing redundant or inconsequential information, changing the type of data, and in general making sure each piece of information is correct and formatted properly. Once the Extract and Transform phases were completed, we just needed to upload our new dataFrame into a database using PostgreSQL to complete the ETL process.
