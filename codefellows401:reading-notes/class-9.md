# Reading Notes


## Code 401 - Advanced Software Development

## Overview of reading notes

These readings delve into the topic of HTTP and cover various aspects related to HTTP requests, such as performing requests in Java using the HttpUrlConnection class.

## What are the five steps in the HTTP Request Lifecycle?

1. Local Processing.
2. Resolve an IP/
3. Estiablish a TCP connection.
4. Sned a HTTP Request.
5. Receiving and Processing the response.

## What are the two things the client needs before it can make an HTTP Request?

Two things the client needs before they can make a HTTP request is:

1. URL
2. IP Address

## Explain the four way handshake and what it does.

The four-way handshake in TCP is a process in which one side initiates the connection termination by sending a FIN packet. Then the other side acknowledges it with an ACK packet. Both sides then exchange FIN and ACK packets to confirm the closure of the connection.

## True or False: When making an HTTP request, you MUST follow any redirect returned by the request. Back up your answer.

False. By default, HTTP libraries follow redirect automatically.

## Which built-in Java class can be used to perform an HTTP request?

The built-in Java class that can be used to perform an HTTP request is `HttpUrlConnection``.

## What HTTP status codes represent a successful response? A redirect? A client error?

* Successful response: 200 to 299. Ex: 200OK
* A redirect: 300 to 399. Ex: 302 Found
* A client error: 400 to 499. Ex: 403 Forbidden

## Things I want to know more about

* just general stuff about each of these concepts. No real questions.