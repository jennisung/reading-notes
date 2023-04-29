# Reading Notes

## Code 201 - Foundations of Software Development: Readings: HTML Lists, Control Flow with JS, and the CSS Box Model


### When should you use an unordered list < ul > in your HTML document? 

Typically, you should use unordered list when you want to group items that do not need to be in a order list and do note need numerical ordering.

### How do you change the bullet style of unordered list items?

If you want to change the type of bullet style (such as circle, disc, square, and maybe triangle) you can change it using CSS by using the 'list-style-type'property and apply it to the element.

### When should you use an ordered list vs an unorder list in your HTML document?

Although, both the ordered and unordered list elements are used to list items. You should use the ordered list element if you want to display a list of items in a specific order. If the order does not have to be in a specific order use unorder list element.


### Describe two ways you can change the numbers on list items provided by an ordered list?

Two ways to change the numbers on list items of an ordered list:

1. Use the "Start" attribute to specify which number you want to start from.
2. Use the "type" attribute  to specify the numbering type (such as roman numerals, numbers, letters).

### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?


### List and describe the four parts of an HTML elements box as referred to by the box model.

**Four parts of box model**

1. **Content Box:** refers to where your contents are contained and displayed. You can manipulate the size by using properties like 'inline-size' and 'block-size' or 'width' and 'height'.
2. **Padding Box:** the padding is the space outside/around the contents and is the white space. You can manipulate the size using 'padding' property. 
3. **Border Box:** the border box surrounds the content and padding. You can manipulate the size using the 'border" property. 
4. **Margin Box:** the margin is the outer layer, that surrounds the content, padding, and border. You can manipulate the size using the 'margin' property.


### What data types can you store inside of an Array?

Arrays are useful way to store a collection of values or items in a single variable name. There are various data types you can store inside of an array. For example, you can store numbers, strings, objects, and other arrays. 


### Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

> const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

Yes, the following people array is a valid array. You can have arrays inside an array. This is called a multidimensional array. To access specific values inside an array you need to understand how arrays are numbered. The first item will have an index of 0, the second a index of 1, and etc. To access a specific item you will then use brackets notation and type the specific number index of the item you want to access.

**example to access 32**

> const age = people[0][1];
console.log(age); 

### List five shorthand operators for assignment in javascript and describe what they do.

**Five shorthand operations for assignment in javascript**

1. **+=** : this shorthand operation will add the value of the two operands and then assign the outcome of the variable to the left.

**example**

Shorthand Operator:

x += f();

Means:
x = x + f()


2. **-=** : this shorthand operation will subtract the value of the two operands and then assign the outcome of the variable to the left.

**example**

Shorthand Operator:

x -= f();

Means:
x = x - f()

3. ***=** : this shorthand operation will multiply the value of the two operands and then assign the outcome to the variable to the left.

**example**


Shorthand Operator:

x *= f();

Means:
x = x * f()

4. **%=** : this shorthand operation will get the remainder on the two operands and then assign the outcome of the variable to the left.

**example**


Shorthand Operator:

x %= f();

Means:
x = x % f()

5. **/=** : this shorthand operation will divide the value of the two operands and then assign the outcome variable to the left.

**example**


Shorthand Operator:

x /= f();

Means:
x = x / f()


### Read the code below and evaluate the last expression and explain what the result would be and why.

>  let a = 10; <br>
 let b = 'dog'; <br>
 let c = false;

>// evaluate this <br>
 (a + c) + b;


The result of this expression would be **10dog** . To solve this, you will first solve the expression inside the parenthesis. In this case, the value **a**, which is te value of 10 is added to the value of **c**, which is boolean of false. Since false is considered 0, the resulting value is a 10. Now, you will add the 10 to the value of **b** which has the value of 'dog'. which would make th outcome value of '10dog'.

 ### Describe a real world example of when a conditional statement should be used in a JavaScript program.

 Conditional statements are useful in javascript as you can use it to make decisions based on the situation or the input. An example of a real world situation of this may be if a employee is being asked to work overtime or not. If the employee works overtime they get paid an extra $100. If not, they don't get any extra income. So, let's say an exmployee says "no" to the overtime they will not get the $100.

>  let overTime = false; <br>
let employeeBenefits; <br> if (overTime === true) {
  employeeBenefits = 100;
} else {
  employeeBenefits = 0;
}


### Give an example of when a Loop is useful in JavaScript.

Loops are useful in javascript as you can use it to run a piece of code over and over again, or run the code with slightly different variation. An example of a loop that is useful in javascript is if you want to just a say a phrase multiple times on your page.

**example**
> for (let i = 0; i < 5; i++) {
  console.log("Hello, world!");
}

### Things I want to know more about