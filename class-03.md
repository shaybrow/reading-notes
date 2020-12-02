# HTML Lists, Control Flow with JS, and the CSS Box Model

[Back to Main Page](README.md)

## Lists

- `<li>` is used for list items in all lists

### Numbered Lists

- aka ordered lists

- `<ol>` creates our list

### Unordered Lists

- `<ul>` makes our list

### Definition Lists

- `<dl>` makes our list

- `<dt>` is the item being defined

- `<dd>` is the definition

### Nested Lists

- you can put multiple lists inside of eachother until you get listless

## Boxes

- never forget that everything in HTML is essentially a box

### Dimensions

- can use `px` `em` or `%` to define those dimensions

- em and % are more popular to deliver a better experience to a variety of screens

- `min-width: Xpx;` and `max-width: Xpx;` help us prevent those boxes from becoming too wide or too narrow

- same goes for `max-height` and `min-height` but vertically

- `overflow: hidden;` and `overflow: scroll` are things we can tell the browser to do if the content becomes larger than it's box

### Border, Margin and Padding

1. Border - right along the edge of the box

1. Margin - just outside the border seperates a given box from adjacent ones

1. Padding - how much space should be between content and the border

- `border-width: top right bottom left`

- `border-style` can change the visual effect of the border

- `border-color` changes the color

### Inline/Block

- by default all elements are either inline or block

- inline means in line with text

- block means it creates it's own new block around it

- `display: inline;` makes a block element display like an inline element and visa versa

## Arrays Again

We use these any time we want to make a list of things related to eachother. You could consider Excel an unlimited number of Arrays

- `var numbers = new Array(1,2,3,4,5,6)` is anoither way to create an array

- remember that the first value in an array is 0 so `numbers.item(0)` would return 1

- `numbers.length;` will tell us how many values are in our array

## Switch Statements

A switch statement starts with a Switch Value

- `switch (page) {
  case 'One':
  title = 'Page 1';
  break;

case 'Two':
title = 'Page 2';
break;

default title = 'Whoops';
break;
}`

- this allows us to present users with different info based on a given variable

### Weak Typing

JS attempts to convert data types that don't make sense into something that does. Because of this we want to always use strict indicators like `===`

### Truthy and Falsy

- due to this weak typing any value in JS can be considered True or False

- an undeclared or empty variable for example is considered falsy or false

- any number other than 0 is considered true

- we can use the fact to check to see whether things exist

### Loops

Loops check whether something is true. If it is, it repeats until the conditions becomes false

- for loops are used for running code a specific amount of times using a counter

- while loops continue to run as long as the condition is true

- do while is similiar to while loops but run once no matter what

- `break` causes a loop to stop immediatelu
