# Reading-notes

## Code 301 - Intermediate Software Development: CRUD

## Overview of reading notes
These readings are important for understanding which HTTP status codes to use for every CRUD app. Additionally, the video is crucial as it guides us through the process of building a REST API.

### In your own words, describe what each group of status code represents:

100’s: Status codes in the 100's refer to informational responses, indicating that the requests have been received and the server is processing them.

200’s: Status codes in the 200's indicate successful responses, meaning that the requests have been received and processed by the server.

300’s: Status codes in the 300's are redirection responses, meaning that the requested resource is located at a different location.

400’s: Status codes in the 400's refer to client error codes, indicating that an invalid request has been sent to the server.

500’s: Status codes in the 500's represent server error codes, indicating issues with the server.

### What is a status code 202?

A status code of **202** means **Accepted** indicating that the request is valid but is not yet done processing.

### What is a status code 308?

A status code of **308** is **Permanent Redirect** indicating that the request has been moved to a different URL permanently.

### What code would you use if an update didn’t return data to a client?

You would use code **204 NO CONTENT** in this situation.

### What code would you use if a resource used to exist but no longer does?

You would use code **410 GONE** in this situation.

### What is the ‘Forbidden’ status code?

The **Forbidden** status code is 403.

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

It makes sure sensitive information is not shared to public

### What is middleware?

Middleware is a code between the client and the server, allowing for the processing for requests and responses of application.

### What does app.use(express.json()) do?

(express.json()) enables to parsing of JSON data.

### What does the /:id mean in a route?

It acts as a placeholder for passing a variable value in the URL.

### What is the difference between PUT and PATCH?

PUT is the overwrite a resource of a specific URL, while PATCH is to make updates to a resource.

### How do you make a default value in a schema?

To make a default value in a schema, you can use the "default" property and input the desired value.

### What does a 500 error status code mean?

A 500 error status code, specifically 500 Internal Server Error,

### What is the difference between a status 200 and a status 201?

200 OK status code indicate the request has been seccessful, and 201 created status code meaning yhe request has been created a new resource.

## Things I want to know more about

* Are there specific status codes we should know?
