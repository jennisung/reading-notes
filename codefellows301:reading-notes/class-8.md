# Reading-notes

## Code 301 - Intermediate Software Development: APIs

## Overview of reading notes

Learning about APIs will be important as they set various rules and protocols for how various components in software interact.

### What does REST stand for?

REST stands for Representational State Transfer.

### REST APIs are designed around a ____.

REST APIs are designed around resources.

### What is an identifier of a resource? Give an example.

A URL that identifies a resource can be considered a identifier. For example:

https://adventure-works.com/orders/1

### What are the most common HTTP verbs?

The most common HTTP verbs are; GET, POST, PUT, PATCH, DELETE.

### What should the URIs be based on?

URIs should ideally be based on nouns (resources) rather than verbs (operations on the resource). 

### Give an example of a good URI.

**Example :**
https://adventure-works.com/orders

/customers/{id}

### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

Having a 'chatty' web API is considered a bad thing as it involves making multiple requests to retrieve or manipulate data simultaneously. This can cause performance issues, impacting the efficiency of the system.

### What status code does a successful GET request return?

A successful status GET method will return a code 200 (OK).

### What status code does an unsuccessful GET request return?

A unsuccessful status GET method will return a code 404 (Not Found).

### What status code does a successful POST request return?

A successful POST request returns a status code of 201 (Created).

### What status code does a successful DELETE request return?

A successful DELETE request typically returns a status code of 204 (No Content). 

## Things I want to know more about

* How will we be using API?
