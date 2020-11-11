# CSS with Style

[Back to Main Page](README.md)

CSS is primarily used to make web sites look pretty.

## Basics

- CSS allows you to separate pages into portions and make changes to individual portions

- rules are associated with various HTML elements

- CSS rules sit inside curlies `{CSS}`

- External CSS refers to CSS referencing a separate CSS page or style sheet

- Internal CSS makes changes to the HTML in-line

## Color

- RGB stands for `(red, green, blue)`

- You can also use 6 digit hex codes such as `#384eee`

- If you're feeling lazy, just name a color like `blue`

- Color picking tools are great for getting the exact color you want

### Foreground

- Typically you will use these to indicate text colors

- Ex. `li {color: blue;}`

### Background

- CSS thinks inside the box so it's easy to create a background color for any portion of your website

- Ex. `nav {color:(100,0,0);}`

### Contrast

- Avoid low contrast at all costs. Nobody wants to squint at your web page

- High contrast is good for small portions of text you want to draw attention to

- Medium contrast will be your go to for most text

### Opacity

- Want to have one thing show over another?

- Ex. `p {color:blue; opacity: 0.5;}`