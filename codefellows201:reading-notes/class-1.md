# Reading Notes

## Code 201 - Foundations of Software Development:


## Overview of reading notes

These reading notes will be important as they provide a quick overview of the workings of the web and a concise summary of how HTML, CSS, and JavaScript works.

## Getting Started

### 1. Compose a short poem describing how HTTP sends data between computers.


### 2. How HTML, CSS, and JS files are “parsed” in the browser.

When web browsers request HTML files from servers, these files will likely contain < link> and < script> elements. These elements will be referencing external CSS and JavaScript files. The order in which HTML, CSS, and JS files are "parsed" is important in how pages are loaded onto a page.

1. When loading a page the HTML file will be parsed first and will look for any < link> and < script> elements that are referencing external CSS and/or Javascript files.

2. As the HTML is parsed through, the web browser will send requests to the server for CSS and Javascript files found in the < link> and/or < script> elements.

3. As the browser parses through the HTML and CSS, it will be producing several things. Such as producing an in-memory DOM tree from the HTML, an in-memory CSSOM structure from the CSS, and compiling and executing the parsed javascript.

4. Lastly, the visual representation of the browser is shown on screen, which users are able to interact with.


### 3. How can you find images to add to a Website?

Images can be found on [Googe Images](https://images.google.com/). Pick an image you'd like, and click to enlarge the image. Once the image is enlarged right-click on the image and click on "Save Image As". Choose a safe location to store the image for later use. It is also important to remember that most images that are on the web will have a copyright. To mitigate the possible issue of violating copyright, select the *Tools* button, then click on the *Usage Rights* tab, and select *Creative Commons licenses*.


### 4. How do you create a String vs a Number in JavaScript? And other variables.

Variable Type| Explanation | Example
--- | --- | ---
String| Add a single or double quote around a text to make it a string | let myAge = 30
Number| No quotes for number| let myName = 'Jennifer'
Boolean | Making a variable that is either true or false value | let myVar = true;
Array | Allows you to store multiple values in the same data type | let myFavFood = ['Apple', 'Pizzza', 10];


### 5. What is a Variable and why are they important in JavaScript?

A **variable** is important because it allows users to create containers to store values in. This is important because you can retrieve the variable and reuse that variable by the assign name you give it. 


## Introduction to HTML

### What is an HTML attribute?

In HTML, an **atribute** contains extra information about an element that doesn't appear in the output.

### Describe the Anatomy of an HTMl element.

**3 main parts of an element:** 

* **Opening Tag:** the opening tag is the name of the type of element you're using, and it is enclosed with an opening and closing angle brackets.

**For example** a paragraph element < p>

* **Contents of element:** the contents of an element. Such as text.  
* **Closing Tag:** this is the same as the opening tag, except is also has a forward slah before the element name or opening angle bracket. **For example:** a paragraph element </ p>


### What is the Difference between < article> and < section> element tags?

The < section> element is used to group related content, whereas the < article> contains independent content and should make sense on its own.

### What Elements does a “typical” website include?

**header:** typically it is situated on the top of the page.

 < header>.


**navigation bar:** the navigation bar will have links to other sections of the site.

< nav>

**main content:** contains the main contents you want to show to users. Although, this will vary, the main content will be in the center of the site.

< main>

< article>

< section>

< div>

**sidebar:** may contain a variety of things like more links, info, ads, etc.

< aside>

< main>

**footer:** this is situated in the bottom of the site and may contain information about the copyright notices, or contact information.

< footer>

### How does metadata influence Search Engine Optimization?

Metadata can influence SEO (Search Engine Optimization) by allowing you to add relevant description about your page ( such as keywords related to the content ) to help your page rank higher in searches in search engines.

### How is the <meta> HTML tag used when specifying metadata?

The < meta> element goes inside the < head> element. And inside the < meta> contains character set, a description about your page, key words, the author information, and etc.

## Miscellaneous

### What is the first step to designing a Website?

Before designing your website, the first step is to think about what you want to accomplish for your website? What are your goals? And how can you reach your goals? This is also called *project ideation*.

### What is the most important question to answer when designing a Website?

Of the three question above, the most important question to answer when designing your website is; "What exactly do you want to accomplish?". This question will be the driving force for the other two questions.

### What are the benefits of using semantic tags in our HTML?

There are several benefits from having a semantic tag:

* influence SEO (Search Engine Optimization)
* It is easier to navigate a webpage when using a screen reader, so this will be helpful for visually impaired users.
* makes it easier to find blocks of meaningful code


### Why should you use an < h1> element over a < span> element to display a top level heading?

Although both the < h1> and < span> headin will create a top level heading, it is best practice to use the < h1> element because the < span> elemant has no semantic value. Thus, it does not have the added benefits from being a semantic tag. 


### Describe 2 things that require JavaScript in the Browser?

Javascript helps you animate images, and add interactive behavior to your webpage.

### How can you add JavaScript to an HTML document?

To add Javascript to HTML, you can place a < script> element in the HTML file to add an external javascript file. The external file will be created in the same directory as your HTML file. You can name the javascript file anyway you want, but it needs to have a .js extension (ex: script.js). Type the file name inside the < script> tag. You can also add javascript code inside your < script> element without adding an external file.

**Example of adding External Javascript to html**

>> < script src="script.js"></script>


## Things I want to know more about

