# Problem Domain, Objects, and the DOM

[Back to Main Page](README.md)

## Problem Domain

- One of the hardest part of programming is defining and exactly understanding exactly what you want your app to do. It's hard to build a bridge without a blueprint.

- Break down a problem domain into small pieces can help you identify exactly what you want to do.

- Use your clients and customers to clearly define your problem domain

## Objects

- group sets of variables and functions to model something you could recognize.

- variables known as properties

- functions known as methods

- literal notation is the most common way of creating an object

- accessing properties or methods uses dot notation `user.birthday`

- contain details of an object in curly braces

## DOM

- tells a browser how to model an HTML page and how JS can change the contents

- often referred to as API or application programming interface

- each node has it's own methods and properties

### Work in a DOM Tree

1. Access the Elements (you can acall a single or multiples)

1. Work with the selected Elements to make changes

### Basic Methods

- `getElementById('id')` calls a single element by it's css id 

- `getElementsByClassName('class')` calls a css class

### Navigating 

- `parentNode` finds the Node containing a given element

- `previousSibling/nextSibling` moves 1 sibling forward or backwards

- `firstChild/lastChild` refers to the first child or last child

- white space can make navigation tricky

### Attribute Nodes

- once you've selected an element you can call and change attributes

- you can also create new attributes using this same method

- inspect, right click element -> inspect element -> properties to see DOM info on web pages