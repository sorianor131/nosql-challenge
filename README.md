# nosql-challenge
Module 12 Homework Assignment - NoSQL Challenge

## Instructions
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Part 1: Database and Jupyter Notebook Set Up
1. Import the data provided in the json file from the terminal. Name the database uk_food and the collection establishments. 

2. Within the notebook, import the libraries needed.

3. Create an instance of the Mongo Client.

4. Confirm that the database was created and loaded properly. 

5. Assign the establishments collection to a variable to prepare the collection for use.

## Part 2: Update the Database
1. Add the new restaurant information to the database.

2. Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.

3. Update the new restuarant with the BusinessTypeID.

4. Remove any establishments within the Dover Local Authority from the database. 

5. Convert latitude and longitude to decimal numbers and RatingValue to integer.

## Part 3: Exploratory Analysis
1. Which establishments have a hygiene score equal to 20?

2. Which establishments in London have a RatingValue greater than or equal to 4?

3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
