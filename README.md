# Ayan Tuladhar
# CSC3916_HW4(Backend)
# 04/17/2022
# Please use the Live preview to view the app

[Live Preview](https://ayanhw5-react-frontend.herokuapp.com/)


[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/b7c844df9df0bfc8b39c?action=collection%2Fimport)


Purpose 
The purpose of this assignment is to create a React Single Page App over your developed API. The interface will allow the users to search for movies, display information about the movie, see stored ratings, and allow the user to enter a rating. 

Pre-Requirements 

• Assignment 3 deployed REACT app that supports SignUp and Logon 

• Assignment 4 that supports reviews 

Requirements 

• Update your API to support storing an image (or image URL) for the movies you have stored.  
You will use the image URL in your React application to show the image of movies 

– New Attribute on the movie collection 

• For this assignment all your endpoints should be protected by JWT authentication 

• Implement the following interfaces 

– User SignUp and User Logon 

▪ Leverage your User mongoDB collection to store new users of the application 

– Main screen should show the top rated movies (show at least 5) 

▪ Your GET /movies endpoint should sort by rating (server side) 

• Update  your  /movies  (with  reviews=true)  endpoint  to  sort  by average rating descending 

– Movie  Detail  screen,  shows  the  Movie,  Image,  Actors  that  were  in  the  movie, aggregated rating for the movie and grid that shows the reviews (username, rating, review) 

– Extra Credit: Movie Search – show results in a grid, accordion or other list control 

▪ Add Search API (HTTP POST) to the API that can take partial movie names or partial actor names 

Acceptance Criteria 

• User is able to Sign-up (name, username, password) 

• User is able to Logon to the application (username, password) 

• User is able to see list of movies and select a movie to see the detail screen (top rated movies displayed) 

• User is able to enter a review on the detail page (enter a rating and comment) – the logged in user’s username will be associated with the review (as captured from the JSON Web Token) 
