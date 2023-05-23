# CRUD

## Which HTTP Status Code to Use for Every CRUD App

From[Which HTTP Status Code to Use for Every CRUD App](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

In your own words, describe what each group of status code represents:

- 100’s = 
Informational responses. The request was received, continuing process.

- 200’s = 
Successful responses. The request was successfully received, understood, and accepted.

- 300’s = 
Redirection messages. Further action needs to be taken in order to complete the request.

- 400’s = 
Client error responses. The request contains bad syntax or cannot be fulfilled.

- 500’s = 
Server error responses. The server failed to fulfil an apparently valid request.

- What is a status code 202?

Accepted. The request has been accepted for processing, but the processing has not been completed.

- What is a status code 308?

Permanent Redirect. 

- What code would you use if an update didn’t return data to a client?

204 No Content

- What code would you use if a resource used to exist but no longer does?

410 Gone

- What is the ‘Forbidden’ status code?

The server understood the request, but is refusing to fulfill it

## Build A REST API With Node.js, Express, & MongoDB - Quick

From[Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

- Why do we need to pull our MongoDB database string out of our server and put it into our .env?

o keep our database credentials secret.

- What is middleware?

A function that is executed before or after a request is handled by an application.

- What does app.use(express.json()) do?

Tells Express to parse the request body as JSON.

- What does the /:id mean in a route?

The route will accept a parameter named id.

- What is the difference between PUT and PATCH?

PUT is idempotent, while PATCH is not.

- How do you make a default value in a schema?

Use the 'default' keyword.

- What does a 500 error status code mean?

An internal server error has occurred.

- What is the difference between a status 200 and a status 201?

A status 200 means the request was successful and the response contains the requested resource, while a status 201 means the request was successful and a new resource has been created.
