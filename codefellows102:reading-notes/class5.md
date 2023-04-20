# Reading Notes

## What is the purpose of CSS?

CSS (Cascading Style Sheets) is used to stylize your website. It can be used to arrange the layout of your website, add visual elements to make it prettier, or do other things to make the website more presentable.

## What are the three ways to insert CSS into your project?

1. **External CSS**: To insert CSS externally, you can use < link > element, and insert it inside the < head > section of HTML.

**For example**

> < head >
> < link rel="stylesheet" href="mystyle.css" >
> < /head>

2. **Internal CSS**:
   To add a CSS into your porject internally, you add the < style > element inside the head section.

**For example**

> < head > <br>
> < style > <br>
> body { <br>
> background-color: linen; <br>
> } <br>
> </ style >  
> < /head>

3. **Inline CSS**: To add inline CSS style, you can add a style attribute to a appropriate element.

**For example**

> < h1 style="color:blue;text-align:center;">This is a heading< /h1>

## Write an example of a CSS rule that would give all < p > elements red text.

**Example**

> p { <br>
> color: red; <br>
> }
