# Reading Notes

## Code 201 - Foundations of Software Development: Readings: CSS Layout

### Flexbox is designed for one-dimensional content. Explain what this means.

Flexible Box Layout Model, otherwise known as flexbox is a layout system that is able to take items of varying sizes, and arrange these items in the best possible layout, making it designed for one-dimensional content.

### Explain the difference between the main axis and cross axis.

It is important to understand main axis and cross axis in flexbox. The main differences from these two axis is that the **main axis** is defined by the *flex-direction* property. Meaning if that is row, your main axis to along the row. The same holds true for column. If it is set to column, then it is along column. Whereas the **cross axis** runs on the opposite direction to the main axis. Thus, if the *flex-direction* is column the cross axis will run by the row.

### How can using certain properties of flexbox negatively impact accessibility?

Using the wrong property to change the visual display of a HTML document can negatively impact accessibility. For example, using the *row-reverse* and *column-reverse* values. In this vase, the restructuring will impact the visual order, not the logical order. This is important because when screen readers read out content is reads the logical order.

### What are some advantages of using flexbox over float?

**List of advantages of using flexbox over float**

* Can make all columns in a set of mulitple columns adjust to the same height, regardless the content it has.
* evenly layout the available space between each children element of a container.
* Vertical center content that is inside a parent.

### How does this topic connect with your long term goals?

Flexbox will be a powerful tool when I get into web development as it'll help me make better responsive web layouts.