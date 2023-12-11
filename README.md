# 12-nosql-challenge

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

In this challenge first we worked with a setup notebook to update the databases.  Updating consisted of adding a new restaurant to the database and removing all documents from the Dover Local Authority.  We also converted number values stored as strings utilizing the update_many function with latitude, longitude and RatingValue.  Once all of the databases were updated we started exploratory analysis.

Eat Safe, Love editors had specific questions to answer, these helped them to find the locations they wish to visit and avoid. These questions are as follows:
  1. Which establishments have a hygiene score equal to 20?
  2. Which establishments in London have a RatingValue greater than or equal to 4?
  3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
  4. How many establishments in each Local Authority area have a hygiene score of 0?  These results are sorted from highest to lowest.
