# Movies ETL


## Overview of the Project
This project is intended to help Amazing Prime to create a database that can be updated on a daily basis. The database will be an automated pipeline that takes in new data, performs the approriate transformations, and loads the data into existing tables.

There were Three (3) files that were analyzed in this activity:

- Wikipedia data
- Kaggle metadata
- MovieLens rating data

## Process and Results

We performed the ETL proccess by adding the data to a PostgresSQL database.

Step 1: Extract the data
Step 2: Transform the data
Step 3: Load the data

We also ran a query on the PostgresSQL database using pgAdmin to confirm the movies table and ratings table.

**Movies Query - to confirm there are 6052 rows of data:**

![Movies_Query](https://raw.githubusercontent.com/Mishabatoon/Movies-ETL/main/Resources/movies_query.png)


**Ratings Query - to confirm there are 26,024,289 rows of data:**

![Ratings_Query](https://raw.githubusercontent.com/Mishabatoon/Movies-ETL/main/Resources/ratings_query.png)
