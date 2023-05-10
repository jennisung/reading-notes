# Reading Notes


## Code 201 - Foundations of Software Development: Readings: Forms and JS Events

## Overview of readin

These readings will be important as we delve further into how to add features to our website using JavaScript. Forms are an important part of many websites because they allow users to input and submit data. Event listeners are useful as they allow you to execute specific triggers from an action by the user.

### Why are forms so important in web development?

**Forms** are a crucial part of web development because it is used to gather wide arrange of information/data from users or allow for interaction with users. 

### When designing a form, what are some key things to keep in mind when it comes to user experience?

**When designing a form, some key things to consider when it comes to user experience:**

* Keep it simple. 
* Don't ask for information you don't need.


### List 5 form elements and explain their importance.

**Five form elements:**

1. **< form> :** every form starts with this element. 
2. **< label> :** this element used as a text label that is used alongside the form element.
3. **< input> :** this element is used data entry or to collect the data.
4. **< textarea> :** this element is used to collect messages or longer lines of text.
5. **< button> :** this element creates a button, which allows the user "submit" their data.


### How would you describe events to a non-technical friend?

In javascript, an event is what allows for things or "events" to happen on a webpage. It allows for some type of reaction to happen. For example, when you click on a button on a webpage and a pop-up window comes on screen.

### When using the addEventListener() method, what 2 arguments will you need to provide?

**Two arguments needed when you use the addEventListener() :**

1. a string, such as "click", "mouseover", or "keydown" that specifies the type of event.
2. A function to call when the event happen.

### Describe the event object. Why is the target within the event object useful?

**Event Object** is a parameter that is automatically passed to the event handler functions. It provides added information and related features to the event. The target in the event object is useful because it allows you to know/identify the element the event reacted to.


### What is the difference between event bubbling and event capturing?

**Event bubbling** and **event capturing** both describes how web sites handles events (or how events are propagated). The difference between the two is that for **event bubbling** the event goes through its parent element and then target element. **Event capturing** is the reverse of this.

## Things I want to know more about

* Where is the data stored when using forms to collect user data?