# Reading Notes


## Code 201 - Foundations of Software Development: 


## Overview of reading notes:

Learning about local storage is important as it is a powerful took to store data. It is also important to know the **Do's and Don't** when it comes to local storage before using it as there are some security risk involved.

### Why would a developer use local storage for a web application?

One of the issues with HTTP as the primary transport layer of the web is the fact it is stateless. This means that when you use a application and close it, the state of it will be reset when reopen. If on a desktop and you close a application and reopen it, the more recent state will be opened or restored. This is where **local storage** will come in handy, in where you can store the state of your interface.


### What information should not be stored in local storage?

Although local storage is a useful tool to store information/data for web application, information that shouldn't be store in local storage is probably sensitive or confidential information. One of the dark sides of local storage mention is that some people abuse it for their personal gain. meaning that they might steal other use information. Thus it is crucial to be mindful of what your store in local storage.


### Local storage can store what type of data? How would you convert it to that type before storing?

**Local storage**, stores data in a form of a string. But you can store different data types by converting them to strings. For **strings** there is no need to convert as it is the proper format. But, for **objects** you use the `JSON.stringify()` to convert the object to a string.

## Things I want to know more about

* Is local data similar to cloud/github?