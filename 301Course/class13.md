# CRUD

## Status Codes Based On REST Methods

### In your own words, describe what each group of status code represents:
* 100’s = Informational
* 200’s = Succesful
* 300’s =  Redirection
* 400’s =  Client Error
* 500’s =  Server Error

### What is a status code 202?

Accepted

### What is a status code 308?

Permanent Redirect

## What code would you use if an update didn’t return data to a client?
204

### What code would you use if a resource used to exist but no longer does?

409

### What is the ‘Forbidden’ status code?

403

----


### Why do we need to pull our MongoDB database string out of our server and put it into our .env?


This section describes the standard format of the MongoDB connection URI used to connect to a MongoDB deployment: standalone, replica set, or a sharded cluster. The standard URI connection scheme has the form: mongodb://[username:password@]host1[:port1][,...hostN[:portN]][/[defaultauthdb][?options]]

### What is middleware?


Middleware is software that lies between an operating system and the applications running on it. Essentially functioning as hidden translation layer, middleware enables communication and data management for distributed applications.

## What does app.use(express.json()) do?

The express.json() function is a built-in middleware function in Express. It parses incoming requests with JSON payloads and is based on body-parser.

### What does the /:id mean in a route?


The req. params property is an object containing properties mapped to the named route “parameters”. For example, if you have the route /student/:id, then the “id” property is available as req.params.id. This object defaults to {}.

### What is the difference between PUT and PATCH?

The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.

### how do you make a default value in a schema?

Your schemas can define default values for certain paths. If you create a new document without that path set, the default will kick in.

### What does a 500 error status code mean?

The HyperText Transfer Protocol (HTTP) 500 Internal Server Error server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request.

### What is the difference between a status 200 and a status 201?

The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page).
Mongoose only applies a default if the value of the path is strictly undefined.


