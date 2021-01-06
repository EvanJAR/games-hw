ANSWERS:

What is responsible for defining the routes of the games resource?
    app.use in server.js is responsible for defining the routes

What do you notice about the folder structure? 
    The server's folder structure seems to have less parts involved in it, the client has more components.

Whats the client responsible for? 
    The client is responsible for the front-end of the web app.

Whats the server responsible for?
    The server is responsible for the back-end of the web app, the routes and the database are contained in the server.

What are the the responsibilities of server.js?
    server.js listens for requests, it defines the routes. 

What are the responsibilities of the gamesRouter?
    It is a function that will take in the data about games and creates the routes for each of the different CRUD commands. 

What process does the the client (front-end) use to communicate with the server?
    Requests which the server listens to. 

What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs
    It takes an optional init object which allows you to set custom settings to the request. 
    It passes the request method (i.e. DELETE and POST).

Which of the games API routes does the front-end application consume (i.e. make requests to)?
    Is it this: http://localhost:5000/api/games/? Provided in GamesService.js 

What are we using the MongoDB Driver for?
    We use the mongoDB driver to connect to the database and work with that data by fetching it.
