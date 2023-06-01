# Reading-notes

## Code 301 - Intermediate Software Development:Putting it all together

## Overview of reading notes

### What is the single responsibility principle and how does it apply to components?

The **single responsibility principle** is a programming technique that helps in determining whether to create a function or object. Ideally, components should have a single purpose. If a component has multiple purposes, it is recommended to decompose and break it up into smaller subcomponents.

### What does it mean to build a ‘static’ version of your application?

To build a static version of you application means before adding any type of interactivity to the application.

### Once you have a static application, what do you need to add?

Once you have a static application, it is important to add reusable components.

### What are the three questions you can ask to determine if something is state?

**Three questions to determine if something is state**

1. Does it remain unchanged over time? If it does, it is not considered state.

2. Does it get passed in from a parent component via props? If it does, it is not typically considered state.

3. Can you compute it based on existing props or component state? If you can derive or calculate the value based on already existing props or component state, it is not state.

### How can you identify where state needs to live?

Identifying where state should reside can be determined by identifying the component that owns or is responsible for managing that specific state.

### What is a “higher-order function”?

A higher-order function refers to a function that can operate on other functions. These functions allow you to abstract over actions, thus are more adaptible.

### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

In the reading, the **greaterThan** function is an example of a higher-order function. In this case, the parameter **n** and returns another parameter of **m**.

### Explain how either map or reduce operates, with regards to higher-order functions.

The **map** method transforms an array by applying a function to each of its contained values/elements and returns a new array containing the values returned by the function.

The **reduce** function is used to combine the elements of an array into a single value. 

## Things I want to know more about

* I'm still abit confused about higher-order function? I would like to see more examples or a simpler explanation of the concept. 