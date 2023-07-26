# Reading Notes


## Code 401 - Advanced Software Development

## Overview of reading notes

The readings delve into security and passwords, discussing various methods for storing passwords. It also highlight the importance of proper password handling to ensure data safety and protection against hackers.

### Define the term “hashing”.

Hashing is a secure method of storing passwords, which involves converting them into a format that cannot be reversed back to their original form.

### Explain to a non-technical friend what a hash function does to a password.

I were to explain hash again, I would say, imagine you just created a new password, the hash function, to make that password more secure when storing it, is to convert it into a unique jumbled-up code that cannot be converted back to the original form.

### What does it mean to ‘salt’ a password?

To 'salt' a password means to add a random and a very long string of bytes (unique string of characters) to the password before being hashed. This is a great way to secure your data.

### What piece of information would a hacker need to access in order to find the ‘salt’ string for your passwords?

To find the 'salt' string for passwords, a hacker would need access to your source code where the string of passwords are stored.

### How does the Blowfish block cipher handle the increased computation speed of new computers?

The Blowfish block cipher used in BCrypt handles the increased computation speed of new computers.

### What are the issue with the two most commong password hashes for Java (“Java password hash” and “Java password encryption”)?

The issue with the two most commong password hashes for Java (“Java password hash” and “Java password encryption”) is; unsalted hash, which means ppasswords are hashed with the unique string/byte added to password. 

## Things I want to know more about

* just general stuff about each of these concepts. No real questions.

