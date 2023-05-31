# Reading-notes

## Code 301 - Intermediate Software Development: React and Forms

## Overview of reading notes:

These readings are important as they provide us with additional tools that we can utilize when delving into React and when we start to build projects using React. We are learning similar materials to what we learned in JavaScript (without React), but with react. Such as building forms. But in addition to use, we're using React to make more concise statements.

### What is a ‘Controlled Component’?

A **Controlled Component** 
refers to form input elements, such as `<input>`, `<textarea>`, and `<select>`, whose values are maintained by React state and are updated based on user input.

### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

It may be more beneficial to update the state as soon as the user enters their responses. This way you can capture the user's input,incase the user refreshes the page by accident.


### How do we target what the user is entering if we have an event handler on an input field?

To target what the user is entering if we have an event handler on an input field, we can use the `event.target.value` property


### Why would we use a ternary operator?

You would want to use ternary operator whenever you want to write more concise conditional statements.

### Rewrite the following statement using a ternary statement:

`if(x===y){
  console.log(true);
} else {
  console.log(false);
}`

`console.log(x === y ? true : false)`

## Things I want to know more about

* Can we still write expressions using the traditional method on react or will that be difficult?