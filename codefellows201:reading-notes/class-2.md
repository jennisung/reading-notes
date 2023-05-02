# Reading Notes

## Code 201 - Foundations of Software Development:Basics of HTML, CSS & JS

## Overview of reading notes

These readings will be important as it will go over basic concepts of HTML/CSS/javacipt and will provide a good introduction on these topics. Getting a solid foundation on HTML/CSS/Javascript will be important as we start developing websites. It will also help soldify some of the things we learned in Code 102.


### Why is it important to use semantic elements in our HTML?

Semantic elements are important in HTML because it makes the HTML more accessible and comprehensible.

There are several benefits from having a semantic tag:

* influence the SEO (Search Engine Optimization)

* It is easier to navigate a webpage when using a screen reader, so this will be helpful for visually impaired users.
* makes it easier to find blocks of meaningful code

### How many levels of headings are there in HTML?

HTML has 6 levels of headings. h1, h2, h3, h4, h5, h6.

**example:**

* **Heading 1(largest/highest):** < h1>

* **Heading 6(lowest/smallest):** < h6>

### What are some uses for the < sup> and < sub> elements?

The < sup> (superscript) and < sub> (subscript) elements are utilized if you're going to makeup things like dates, chemical formulas, and math equations. 

### When using the < abbr> element, what attribute must be added to provide the full expansion of the term?

Whenever you use the < abbr> element, the title attribute must be included to provide the full expansion of the term.

### What are ways we can apply CSS to our HTML?

You can apply CSS to HTML using three methods:

1. External stylesheet: to use this method, you will need to create a external file with a .css extension (ex: style.css). Once you created an external CSS stylesheet, add the file to the HTML using a < link> element. 

 **example**

  > < head>
    < link rel="stylesheet" href="styles.css" />
  < /head>

2. Internal stylesheet: using this method, you will need to type our your CSS inside a < style> element which is situated inside the < head>

3. Inline styles: using this mehtod, the css is typed and contained in the style attribute.

> < p style="color:blue;">Example of an Inline style method of adding CSS to HTML</p>

### Why should we avoid using inline styles?

You should avoid using the inline method to add CSS because it is difficult to read and and understand, as the HTML gets mixed up with the CSS. In addition, it is difficult to maintain the CSS.

### Review the block of code below and answer the following questions:

1. What is representing the selector?
The representing selector in this code is the h2.

2. Which components are the CSS declarations?
The components that are the CSS declaration is **color: black;** and **padding: 5px;**. 

3. Which components are considered properties?
The color and padding are considered properties in this line of code

> h2 {
     color: black;
     padding: 5px;
   }


### What data type is a sequence of text enclosed in single quote marks?

A data type where a sequence of text is enclosed in a single quote marks is called a string.

**example:**
> let exampleString = 'This is a string.'

### List 4 types of JavaScript operators.

Operator | Explanation | Example
--- | --- | ---
Addition| Adding two numbers or combining two strings | 6 + 9; <br> 'Jennifer' + 'Sung';|
Subtract, Multiply, Divide | Similar to how you would use these operators in math | 10 - 5; <br> 4 * 5; <br> 9/3; |
Strict Equality | compares to see if two values are equal and the same data type. It will return true or alse | let myVar = 10; <br> myVar === 11; <br> **returns false** <br> let myVar = '4'; <br> myVar === 4; <br> **returns false** |
Not equal | returns the opposite. If something is true, then it will be turn to false. | let myVar = 3; <br> myVar !== 3; <br> **returns false** |

### Describe a real world Problem you could solve with a Function.

Functions are useful since you can reuse a block of code without having to retype it. One example of using a function to help solve a real-world problem is using it to help you validate a password if someone is trying to log into their account on a website. For example, the parameter of a function can be the password, and it needs to be compared to the criteria that need to be met, for the password to be validated.


### An if statement checks a __ and if it evaluates to ___, then the code block will execute.

An if statement checks a **condition** and if it evaluates to **true**, then the code block will execute.


### What is the use of an else if?

A **else if** is useful if you want to add extra outcome/choices to your **if...else**

### List 3 different types of comparison operators.

Comparison operators| Explanation | 
--- | --- |
=== and !== | to see if one value is the same as one another, or not the same as one another. |
< and > | seeing if one value is greater than or less than another value |
<= and >= | seeing if one value is less than or equal to, or if one value is greater than or equal to another value



### What is the difference between the logical operator && and ||?

The difference between the logical operator '&&' (AND) and '||' (OR) is that for the '&&' operator, when you chain together two or more expressions, all of them have to be true for the whole expression to come back true. Whereas, the '||' only one of the the expression needs ot be true for whole expression to be true.

## Things I want to know more about

* Uses for either if else statement or switch statements.

