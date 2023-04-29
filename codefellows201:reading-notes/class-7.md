# Reading Notes


## Code 201 - Foundations of Software Development: Readings: Object-Oriented Programming, HTML Tables


### Explain why we need domain modeling.

Domain modeling is an important process that enables the creation of a conceptual model to gain an understanding of a specific problem. A well-designed domain model can help to confirm the understanding of the problem for various stakeholders to help find effective solutions. In addition, it can improve communication as it helps establish a common vocabulary to be used between technical and business teams to help avoid misunderstanding.


### Why should tables not be used for page layouts?

**The three reasons tables should not be used for page layout:**

1. **Accessiblity issues:** tables used for layout make it hard for those using screen readers to understand the contents of a page.  
2. **Harder to Maintain and complex:** table layouts have complex markup structure making it harder for the code to debug and maintain.
3. **Not automatically responsive:** tables have default sizes, so trying to style the table layout will be harder and vary across devices.

### List and describe 3 different semantic HTML elements used in an HTML < table>.

**Three different semantic HTML elements used in an HTML < table>:**

1. **< th> :** this element is used to create the header cell at the start of a row or column.
2. **< col> and < colgroup>** this feature allows you to set the styling for a column of data in one place.
3. **< tr>** used to set the row of cells in a table.

### What is a constructor and what are some advantages to using it?

A constructor is special function that allows you to initialize new object instance. In order to call the constructor you will use the **new** keyword. A constructor is helpful when you're creating more than one object using a single object definition.

### How does the term this differ when used in an object literal versus when used in a constructor?

When you use the **this** term in object literals you're referring to the object itself. Whereas the **this** keyword in constructor is when the instance of an object is created.

### Explain prototypes and inheritance via an analogy from your previous work experience.

To help better explain prototypes and inheritances, I will use an anology from my own work experience to explain these two concepts. As a teaching assistant for a math course at a college, I taught students how to solve various problems using my own method to solve a problem, a basic step-by-step guide or method. Let's consider this an analogy for prototype.

Now, every student is different, with vastly different learning styles and each students have their own unique techniques to solve a problem. As students solve problems they may solve the problem different due to their own unique way of going about a problem. They use the basic methods I showed them and they also add their own spin to solving the problem. This is considered inheritance. 