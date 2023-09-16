# nosql-challenge
Module 12 Challenge UM Bootcamp

# Background
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating.  You've been contracted by the editors of a food magazine, *Eat Safe, Love*, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Part 1: Database and Jupyter Notebook Set Up
1. I started by importing the data provided in the establishments.json file from the Terminal.
2. I imported the dependencies of PyMongo and Pretty Print.
3. Then I created the database within an instance of the Mongo Client.
4. Uk_food was created as the database with a collection of establishments.

## Part 2: Update the Database
1. A new business called Penang Flavours was added to the database. 
2. BusinessType was updated for the new business. This was done using update_one.
3. Update many was used to change number values on latitude, longitude and RatingValue.  This was done using update_many.

## Part 3: Exploratory Analysis
Exploratory analysis was done on the documents within the MongoDB with the following questions:
1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a Rating Value greater than or equal to 4?
3. What are the top 5 establishments with a Rating Value of 5, sorted by lowest hygiene score, nearest to the new restaurant added - Penang Flavours?
4. How many establishments in each Local Authority area have a hygiene score of 0?  Sorted from highest to lowest and displaying the top ten local authority areas.

Completing the analysis including using the count_documents, aggregation, pipeline functions.

# Credits
Thank you to the tutor, Limei Hou, who helped me with the setup_starter  part of the assignment.  She was incredibly helpful at explaining how to approach getting the answers.

Thank you to Hunter Hollis, instructor, and TA's Randy & Sam for all of their teaching and support during this week's lessons of the Bootcamp.