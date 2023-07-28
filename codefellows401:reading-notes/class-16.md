# Reading Notes


## Code 401 - Advanced Software Development

## Overview of reading notes

The readings provided give an overview of the Spring Security architecture and its key components

### What does it mean to authenticate a user?

Authentication or "access control" (per spring.io) refers to verifying the identity of a user, typically it involves verifying the user's credentials, such as a username and password.

### What does it mean to authorize a user?

Authorizing a user refers to allowing or granting access to a system.

### What are the three possible outcomes of the AuthenticationManager’s authenticate() method?

**In sptringboot, the three possible outcomes of the AuthenticationManager’s authenticate() method are :**

1. Return an **Authentication** (if authentication is true), if the input is a valid principal.
2. Throw an **AuthenticationException** is the input is a invalid principal
3. Return **null** if the AuthenticationManager cannot decide validity or invalidity.


## Things I want to know more about

* just general stuff about each of these concepts. No real questions.