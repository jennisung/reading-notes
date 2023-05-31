# Reading-notes

## Code 301 - Intermediate Software Development

## Overview of reading notes

These readings are important it provides us with useful functions we can utilize when we get into react, such as .map(), and the spread operator.

### What does .map() return?

The .map() function returns a new array with the results of applying a function to each index of the previous array.

### If I want to loop through an array and display each value in JSX, how do I do that in React?

If you want to loop through an array and display each value in JSX, you can do that in react by using the Javascript .map() function.

### Each list item needs a unique ____.

 Each list item needs a unique **Key**

### What is the purpose of a key?

The purpose of a key is to provide a identifier for each item in a list of elements and needs to be included whenever your create lists of elements. 

### What is the spread operator?

A spread operator is a syntax that can be used to add items to an array, combine/manipulate objects or arrays, and spread out an array into a function argument.

### List 4 things that the spread operator can do.

**Four useful things a Spread Operator can do**

1. Adding or expanding an array, by adding an item to a array
2. Merging or combining properties and methods to a new object
3. Adding an item to an array in React state
4. Converting NodeList and argument objects to array.


### Give an example of using the spread operator to combine two arrays.

`let array1 = [1, 2, 3];`

`let array2 = [4, 5, 6];`

`let twoArrays = [...arr1, ...arr2];`

### Give an example of using the spread operator to add a new item to an array.

`let numbers = [1, 2, 3];`

`let newNumber = 4;`

`let updateNumberList = [...numbers, newNumber];`

### Give an example of using the spread operator to combine two objects into one.

`let johnObj = { name: 'John', age: 30 };`

`let addObj = { gender: 'Male', occupation: 'teacher' };`

`let johnCombined = { ...johnObj, ...addObj };`

## Things I want to know more about

* Other useful functions or other most used functions we'll bee using when we get into react?