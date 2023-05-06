# Reading Notes


## Code 201 - Foundations of Software Development: Readings: Problem Domain, Objects, and the DOM

## Overview of reading notes:

These readings are important as it delves into objects and DOM. Objects is important to understand as it helps you to organize data and functions. DOM is important as it allows javascript to interact with webpages.

### How would you describe an object to a non-technical friend you grew up with?

In javascript, a object is sort of like a container that stores related information and functionality together. For example, in javascript a object may be a container for various variables or functions.

### What are some advantages to creating object literals?

In javascript, a object literal means that you're writing out the object contents as you write it out for your code. Some advantages of object literal is useful if you're creating more than one object with similar properties/methods, you can save time by reusing that method for every object created for that literal. 

### How do objects differ from arrays?

A key difference between objects and arrays is that objects store related data and functionality. While arrays store information store a list of data in a single variable. In addition, objects can store functions, while arrays you can't.


### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

While it is better to use dot notation to access an object's property, as it is easier to read. It is preferred to use bracket notation when you cannot use the dot notation to access the value because the property name is contained in he variable. In this instance it is better to use the bracket notation to access the value. 


### Evaluate the code below. What does the term **this** refer to and what is the advantage to using **this**?

> const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function () {
    console.log ( `${this.name} is ${this.age*7} in human years`); <br>
  } <br>
}

The **this** term in code shown is refers to the "dog' object. Using **this** is useful when you have created several objects with similar properties.methods because it allows you to reuse the method definition for every object created.

### What is the DOM?

**Document Object Model (DOM)** is an application programming interface for web pages. It represents the web page so that you can change the structure, style, and contents of the document. Basically, it allows the elements and contents of a page to interact using javascript.  


### Briefly describe the relationship between the DOM and JavaScript.

DOM is important as it allows the elements and contents of a page to interact using javascript. Thus allowing you to manipulate the behavior of the contents of your page.

## Things I want to know more about

* Are there any best practices to keep in mind when working with the DOM? Like for accessibility purposes?
