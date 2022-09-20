# SQL_QUERY_IMDB_DATASET_Analysis

This Project is based on IMDB Dataset Analysis with the help of SQL as well as some Python Libraries

LINK: https://www.kaggle.com/datasets/mugojosephwamiti/imdb-sqlite-dataset

# PLANNING/APPROACH

STEP1: connect database sqlit3.connect(database_name)
STEP2: Use the cursor function - Database_variable.cursor()

# WORKFLOW

1. I will establish a connection to the SQLITE Database by creating a connection object
2. I will create a cursor object using the cursor() method
3. I will execute the query cursor_variable.execute('query')
4. Fetch the data then use fetchall() method of the cursor variable/object
5. I will create a DataFrame w.r.t the SQlite
6. Data Analysis - Data Manipulation, Data Exploration, Data Cleaning, Data Visualization
7. I will write a conclusion at every step

# ANALYSIS BEING DONE

1. How many movies are present in the movies table
2. Finding out these 3 directors: James Cameron, Luc Besson, John Woo
3. Finding all the directors with the names starting with steven
4. Counting all the female directors
5. Finding the name of the 10TH First Female directors
6. Finding the top 3 most popular movies
7. Finding the top three most bankable movies 
8. Finding out the most Awarded average rated movie since January 1st, 2000
9. Finding all the movies that has been directed by Brenda Chapman
10.Finding out the director who has made the most movies
11.Finding out the director who is most bankable
12.Finding out the Top 10 highest budget making movies
13. Finding the top 10 revenue making movies
14. Finding the top 10 most popular movies with the highest rating
15. Finding the top 10 directors with the number of movies and revenue where revenue should be taken into account for doing the new analysis
16. Finding the top 10 directors with the number of movies and revenue where movies should be taken into account for doing the new analysis
17. Give the title, release date, budget, revenue, popularity and vote average of those movies made by steven Spielberg


# DEMONSTRATION VIDEO
https://user-images.githubusercontent.com/91910681/191363796-2c09f591-6eff-4086-bd4a-1a1aa8839876.mp4

