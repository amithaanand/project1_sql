# project_works
Text contains SQL queries and commands related to managing and querying a table name healthcare_data_bkt and netflix_movies_bkt in a Hive environment. Here's a brief description of the content:

Project 1: Helathcare datasets
1. Table Creation and Loading :  begins with the creation of a table healthcare_data ,loading data into it from a csv file downloaded from Kaggle.Then create bucket table healthcare_data_bkt partitioned by adm_data and clustered by blood_type.
2. SQL Queries : various sql queries are performed to extract specific information
   <br>
   Q1.find how many are there with arthritis above age 50?
   <br>
   Q2.Write a query to fetch all the male patients name who are having either of the diseases  ‘Asthma’ and ‘Hypertension’ ?
   <br>
   Q3.print all patients having name starts with 'Ra'
   <br>
   Q4.fetch the count of patients  who were admitted in the room no 392?
   <br>
   Q5.select * from healthcare_data_bkt where insurance_pro='UnitedHealthcare' limit 5;
   <br>
   Q6.fetch details of patients under 'Michael Chang' and hospital 'Schultz-Powers'?
   <br>

Project 2: 100 Best movies on Netflix
   <br>
1.Table Creation and Loading :  begins with the creation of a table netflix_movies ,loading data into it from a csv file downloaded from Kaggle.Then create bucket tablenetflix_movies_bkt partitioned by year and clustered by score.
   <br>
2. SQL Queries : various sql queries are performed to extract specific information
   <br>
   q1.find the title of movie who got highest and lowest score.
   <br>
   q2.find the query to retrieve movie_title and maximum score for each movie from the table.
   <br>
   q3.print all movie names with rank and year it released starting with 'Th'.
   <br>
   q4.find top 10 movies released and in which year released.
   <br>
   q5.find the movie directed by 'Paul Greengrass' and cast of the movie.
   <br>
   q6.list all movies released in 2019 and find score of each movies.
   <br>
   q7.list all movie directors whose name is starting with 'Pa'.
   <br>
   q8.list last 10 movies from the table along with name of directors.
   
    
