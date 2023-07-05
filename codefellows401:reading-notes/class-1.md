# Reading Notes

## Code 401 - Advanced Software Development

## Overview of reading notes

These explanations provide a brief overview of Java programming and highlight some differences between Java and JavaScript. They also include examples to illustrate how Java operates differently from JavaScript.

## What does “strong typed” mean?

In programming, strong typing refers to how variables have specific data types, and operations between variables are restricted to their respective data types.

## What are the primitive data types?

Primitive data types are predetermined and given names from reserved keywords. Each primitive data value is independent and does not share its state or data with other primitive values.

**Eight data types supported by Java:**

* byte
* short
* int
* long
* float
* double
* boolean
* char


## Explain to a non-technical friend the difference in how compilation works in Java and JavaScript.

JavaScript is an interpreted language, where the code is executed and read by the JavaScript engine in web browsers or other JavaScript runtime environments. On the other hand, Java code is compiled into bytecode using a Java compiler. The bytecode is then executed by a Java Virtual Machine (JVM), 

## Does code complining mean that it works correctly?

No, code compiling does not mean that it would work correctly. The compilation process helps "translate" the code to human readability. However, there may still be logical errors and bugs in the code.

## How many keywords does Java have?

In Java programming, there are 50 keywords.

## How do you print words to the console in Java?

`public class printWord {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
`
## Things I want to know more about

* Since javascript can be inspected/written in web browsers, I'm assuming you can't inspect/write java code in web browsers? Based on the readings?