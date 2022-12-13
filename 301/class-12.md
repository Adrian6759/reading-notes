# Class 12 Notes

Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:

100’s = These will tell you that the header part of the request was received and the other aprt may or may not be received.
200’s = These are codes that indicate successful requests.
300’s = Codes that tell you something is not available right now.
400’s = These are for bad requests send from the client.
500’s = These are server errors that could be due to a number of different things.
2. What is a status code 202?
It means the request was accepted but it will take more time to process.

3. What is a status code 308?
It indicated a permanent redirect when there is a new URL.

4. What code would you use if an update didn’t return data to a client?
204
5. What code would you use if a resource used to exist but no longer does?
410 GONE
6. What is the ‘Forbidden’ status code?
403

Build A REST API With Node.js, Express, & MongoDB

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
Because when we deploy our application, we will not be using our local host.

2. What is middleware?
Code that runs when the server gets a request but before it runs through your route.

3. What does app.use(express.json()) do?
It lets our server accept json. App.use allows us to run any middleware we want.

4. What does the /:id mean in a route?
This means that it is a parameter and it gives us access to whatever is passed through before the slash.

5. What is the difference between PUT and PATCH?
Put updates all information while patch only updates the information that is specified.

6. How do you make a default value in a schema?
You can create it by using "default:" in the schema.

7. What does a 500 error status code mean?
It means that there is an internal server error.

8. What is the difference between a status 200 and a status 201?
201 is for create operations and 200 is not.
