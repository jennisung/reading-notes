# Reading-notes

## Code 301 - Intermediate Software Development: In memory storage

## Overview of reading notes:

These readings are important as we learn about various tools we can use to debug our code, and we also learn about the process of call stacks.

### What is a ‘call’?

When you **call** in javascript call-stack you are executing the function.

### How many ‘calls’ can happen at once?

Multiple **calls** may be executed, but they are executed one after the other in a sequential manner.

### What does LIFO mean?

LIFO stands for "Last-In, First-Out." And it means that the last function pushed into a tack is the first to pop out, when that functions returns.

### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

**Call Stack**

|       |
|_______|
|       |   function C
|_______|
|       |   function B
|_______|
|       |   function A
|_______|

 1. Function A invokes first
 2. After function A, function B is invoked
 3. After function B, function C is invoked, and is removed from callstack.
 5. Then step 3 is repeated for function B and function A, in that order.


### What causes a Stack Overflow?

Stack overflow happens when a recursive function (a function that calls itself), without an exit point.

### What is a ‘reference error’?

A **reference error** occurs when a variable you used, has not been properly declared.

### What is a ‘syntax error’?

A **syntax error** occurs when you have something that cannot be parsed or interpreted.

### What is a ‘range error’?

A **range error** occurs when a value is not within acceptable length or range.

### What is a ‘type error’?

A **type error** occurs when a operation is performed using an inappropriate type(number, string,etc), making it incompatible.

### What is a breakpoint?

A breakpoint is a debugging feature developers use to pause the execution of a code at a specified line. This helps developers pinpoint the bug in the code.

### What does the word ‘debugger’ do in your code?

The word **debugger** in you line of code refers to the debugging tool or function.

## Things I want to know more about

* Other tools that we can use to debug?