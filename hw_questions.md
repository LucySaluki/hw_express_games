# Express Homework

## Questions

1. What is responsible for defining the routes of the `games` resource?
- gameRouter in create_router.js
2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?
 - client is reponsible for interactions with the user and transfer of information to the server
 - server is reposnible for packaging up the information in either direction and interacting with the database for data/collections and client for requests and responses
3. What are the the responsibilities of server.js?
- server.js manages the connection to the database and the router
4. What are the responsibilities of the `gamesRouter`?
- gamesRouter defines the routes
5. What process does the the client (front-end) use to communicate with the server?
- GameService uses a fetch methods to retrive, post and delete information
6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch] on the MDN docs
- the second argument is an init object to allow the control of additional settings, in this case it is use to put the entered data into string JSON format
7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
- Index, create, delete
8. What are we using the [MongoDB Driver] for?
- callback and promise based interaction with the database
9. Why do we need to use [`ObjectId`] from the MongoDB driver?
- to convert the string id into an object recognisable by the database
