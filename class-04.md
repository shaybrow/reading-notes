# HTML Links, JS Functions, and Intro to CSS Layout

## Links

links are very important because they let you move from one web page/site to another or even to other parts of the same page

- `<a href="https://www.google.com">Google</a>` will display google and take you to google.com

### Linking

- `<a>` is what you will use

- type out the full url like shown above to link to other sites

- when linking to the same site the domain name does not need to be indicated

### Directory Structure

- the top level folder is known as the root

- related pages stay in the same folder

- the homepage should always be index.html

- content management systems will often take care of these for you

- each page and img will have it's own url on the site

- root folder contains index.html and folders for the other content

### Other Types of Links

- `mailto: xyz@something.com` links an email address

- `<a href="xyz.com" target="_blank">` opens the page in a new window

- you can use css ids to link to different parts of the same web page as well as specific parts of other pages

## Layout

This is how we control where things sit on the page

### Key Concepts

- never forget that every HTML element is essentially in it's own box

- block elements start on a new line

- inline elements flown in between surrounding text

- if one block element sits inside another the outer box is the parent element

### Controlling the Position

- normally each block element appears on a new line even if the width is reduced

- relative positioning is when the box is positioned compare to where it would have normally been placed

- absolute elements are fixed in place no matter how far you scroll

- `position:relative`

- `position:absolute`

- `position:fixed`

- `z-index:` can be used to overlap elements

- `float` lets us push elements to the left or right and even side x side and create columns

- 960px wide is a good size to aim for when creating a web page

- there are different layout strategies one can use when approaching building a web page

## Functions

- let you group a series of statements together to do a specific thing eg `function showPicsOfMyCat{}`

- `showPicsOfMyCat();` would call the function

- `showPicsOfMyCat(sleeping, eating)` would be how we which info to use

- `function` is the function keyword and `showPicsOfMyCat` is the name of the function while you would write code inside of the `{}`

- this helps us keep our code organized and easy to read

- info given to functions are called parameters

- if a function provides a repspone that is known as a return value

- `return meow;` would be how we return something from a function

- functions can also be stored inside of variables and won't be named

- variables declared inside of functions can only be used inside of that function

- local variables inside of functions are more space efficient

## 6 Reasons for Pair Programming

- 2 people code together, 1 person typing and navigating menus while the second person does the big thinking 

- this allows programmers to talk out their process and become more familiar with listening, speaking, reading and writing code

- paired coding has been shown to be very efficient

- when two people work together an experience is much more engaging

- learning from eachother creates a broader skillset

- this is an easy way to practice social skills for the real world

- this practice is often used in job interviews

- since many companies use this strategy, being familiar with it will help integrate into a job

