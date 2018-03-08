We would like to give you a simple explanation about how are code works , to make it easier for you to understand it. 
Out project consists of 2 parts : First we have the Java program which collects and stores all the data about the movies and second we have HTML code to support the visibility of our project. 
Let's talk about the implementation of the code: 
We used special API key given us by TMDB website which we used to collect all the data about the movies, we focused on the top rated movies on TMDB and went through all the pages in the database to get the information using Unirest requests. 
The data received in a form of Json objects and we processed it and created a Movie object and a Person object. To be able to keep track the amount of male and female in the film industry we mapped the movies according to their release date , and to each person we stored his gender. 
we used the Spring platform of java that ables to use  a controller. the controller waiting for requests from the user of the website (the user chooses a decade, a genre and a role which he wants to find information about) and process the information to send back to the website. 
we implimented a function, that recieves a decade and colculates the precentage of wemen and men for every year in this decade.
at the javaScript side we used an http requests to send to the controller the choise of the user.
also, we used  a tool for building the graph acording to the information sent from the controller. 

