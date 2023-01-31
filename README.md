# User, Occupation and Movies, Ratings Data Exploration using Apache Hive 

## Introduction 
In this project, the objective was to analyze the "User, Occupation, Movies, and Ratings" dataset using Apache Hive. The data was processed and analyzed using Hive's SQL-like query language and MapReduce framework, making it easier to handle large datasets. The focus of the analysis was to provide a comprehensive breakdown of the data and uncover key insights into user preferences and trends.

The first step in the analysis was to load the data into Hive and create a table for querying. The data was then displayed in a tabular format, allowing for a visual inspection of the data. The next step was to print the schema of the table, providing a structured overview of the variables and data types in the dataset.

To further refine the analysis, the data was filtered to show only those observations where the user's age was greater than 25 and the occupation was specified. This helped to focus on the most relevant data and identify trends in user preferences.

The data was then grouped by occupation and the count of users in each occupation was calculated. This provided a summary of the data by occupation, allowing the analysis to determine the occupations where the most users were active and where the preferences were the strongest.

Finally, the data was used to find the user with the highest number of ratings, as well as their age and user ID. This provided valuable insights into the users who were most active in rating movies and could help in understanding the preferences of these users.

In conclusion, this project demonstrates the power of Apache Hive in performing data analysis and uncovering valuable insights from the "User, Occupation, Movies, and Ratings" dataset. By using Hive's SQL-like query language, the data was queried and analyzed with ease, providing valuable information for decision-making purposes.

## Tools Used
- Ambari
- Apache Hive

## Project Screenshots

- Question 1: Find out the Occupation of all the users

![image](https://user-images.githubusercontent.com/69835617/215888401-3b80d4f4-f310-42b0-a10f-e06c842e9d45.png)

![image](https://user-images.githubusercontent.com/69835617/215888424-9c145cdb-1a1e-4434-8207-e7e13bf46c43.png)


- Question 2: Find out numbers of non-adults (users with age less than 18) who have rated movies

![image](https://user-images.githubusercontent.com/69835617/215888441-f204c0aa-a046-4b09-80c2-7eacc64fe9dd.png)

- Question 3: Find out the count of users by occupation where user age is more than 25

![image](https://user-images.githubusercontent.com/69835617/215888652-c2726d0d-f066-4d5e-a58e-ca387171f92d.png)

![image](https://user-images.githubusercontent.com/69835617/215888672-b0f0f47b-5142-4b73-8284-20fed543abf0.png)

![image](https://user-images.githubusercontent.com/69835617/215888698-26763bd2-ad0a-42cf-b695-7df6d913b558.png)

Question 4: Find the user id & age of the user with the most number of ratings 

![image](https://user-images.githubusercontent.com/69835617/215888757-b9cba099-10d0-47da-8a0d-097e7dcad8a4.png)
