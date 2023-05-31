# Reading-notes

## Code 301 - Intermediate Software Development: State and Props


## Overview of reading notes

As we delve into React, it is important to gain a understanding of various concepts, such as component lifecycle events, to understand the behavior of components at different stages. In addition, knowing the difference between props and state is important as they serve different purposes and are used in different scenarios.

### Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Based on the diagram provided in the readings, the render happends first before the componenetDidMount.

### What is the very first thing to happen in the lifecycle of React?

Based on the diagram provided in the readings, the very first thing to happen in the lifecycle of React is the "mounting" phase


### Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`

**Order of Lifecycle Events**

1. Constructor
2. Render
3. componenetDidMount
4. React Updates
5. componentWillUnmount

### What does `componentDidMount` do?

`componentDidMount` phase is when an compenent is created and inserted into the DOM. 

### What types of things can you pass in the props?

You can pass functions or componenets.

### What is the big difference between props and state?

One of the big difference between props and states is that
props you pass into a componenet and outside of that componenent. Whereas, state is handled inside of that componenet.

### When do we re-render our application?

A application is re-rendered when there are changes in the props/state component.

### What are some examples of things that we could store in state?

If there are things that you want to change/update you need to store that in state, so that it is properly rendered.

## Things I want to know more about

* I'd like some more examples about how state/props is used in react. 