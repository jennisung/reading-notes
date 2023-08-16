# Reading Notes


## Code 401 - Advanced Software Development

## Overview of reading notes

These reading delve into Room and DAO in the context of Android data management. 

### What database engine is Room wrapped around? Do you think this is a good choice? Why or why not?

Room is a persistence library, it is wrapped around SQLite,  a abstraction later that helps steamline database access. This is a good choice because it provides several benefits; compile-time verification of SQL queries, convenience annotations, steamline database migration paths.

### Do Rooms have any similarities to JPA?

Yes, Rooms have similarities to JPA. Both use specific annotations to define how objects are mapped to database tables. For example these are primary keys such as `@Entity`, `Primary Key`, and `@Id`. Also in Room, DAOs are used to define methods for accessing database, JPA also uses similar concepts like repositories to handle data access.

### Describe a DAO in your own words

DAO (Data Access Object) provides methods that allow you to perform certain operations in your app to manage data. Essentially, it deals with CRUD operations (Create, Read, Update, Delete) used in Javascript and Java. In DAO, these methods that your app can use are designed to query, update, insert, and delete data within the database.

## Things I want to know more about

* just general stuff about each of these concepts. No real questions.