# Reading-notes

## Code 301 - Intermediate Software Development: Functional Programming

## Overview of reading notes

These readings delves into more node.js concepts and about functional programming concepts. These will be important as we get into more backend programming.

### What is functional programming?

Functional programming is a programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

### What is a pure function and how do we know if something is a pure function?

A pure function always returns the same result when given the same arguments, and it does not cause any observable side effects.

### What are the benefits of a pure function?

Some benefits of pure functions are that they are easier to test since they consistently produce the same output for the same input. They also have no side effects, meaning they don't modify external state, making them easier to debug.

### What is immutability?

**Immutability** refers to when a state cannot change, once it is created.

### What is Referential transparency?

**Referential transparency** refers to a property of a function where it consistently yields the same results for the same input.

### What is a module?

A module is a reusable code with a specific functionality, basically just a javascript file. 

### What does the word ‘require’ do?

The word **require** lets you import modules.

### How do we bring another module into the file the we are working in?

You need to use the **require** function, with the path name.

### What do we have to do to make a module available?

To make a module available for use, you have desired functions,variables, or objects from the module.

## Things I want to know more about

* More examples of pure functions or uses.