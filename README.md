# Backend Intern Hiring Task - 2


## Problem Statement
Load the sample dataset into your MongoDB Atlas cluster (use a free M0 cluster).  
Solve the following tasks by writing MongoDB queries (aggregation pipelines).  


## Questions
1. **Find the title of the movie along with all comments associated with it.**  
   Expected Output Schema:  
   ```json
   {
     "title": "string",
     "comments": [
       {
         "name": "string",
         "email": "string",
         "text": "string",
         "date": "ISODate"
       }
     ]
   }
   ```
 2. **Count the number of comments for each movie.**  
   Expected Output Schema:  
   ```json
   {
    "title": "string",
    "commentCount": "integer"
   }
   ```
3. **Find the top 5 movies with the highest average IMDb rating along with the title, IMDb rating, and total number of comments.**
  Expected Output Schema:
  ```json
   {
    "title": "string",
    "imdbRating": "double",
    "commentCount": "integer"
   }
   ```
4. **List all unique cast members across movies and count how many movies each appeared in.**
  Expected Output Schema:
  ```json
   {
    "castMember": "string",
    "movieCount": "integer"
   }
   ```
5. **Find movies released before 1950 with an average IMDb rating of 7.0 or higher, including their title, IMDb rating, release year, genres, and the first 2 comments (if any).**
  Expected Output Schema:
  ```json
   {
    "title": "string",
    "releaseYear": "integer",
    "genres": ["string"],
    "imdbRating": "double",
    "comments": [
      {
        "name": "string",
        "text": "string"
      }
    ]
}
   ```

Thank You , please review the ans.
