# Object-Oriented Programming, HTML Tables

[Back to Main Page](README.md)

## Domain Modeling

- a model to resolve a specific problem

- describes objects, their attributes and actions and any limitations

- make sure to use small methods that do one job well

- store new objects in variables so you can access later

- use `this` to access object properties from inside the object

## Tables

- use to present info in grid format

- `<table>` to create a table

- `<th>` for table headings

- `<tr>` for table row and `<td>` for table data

- `<td colspan="number of columns">` to indicate a piece of data you want to span across multiple columns

- `<td rowspan="number of rows">` for same thing but rows

- `<thead>` indicates the headings of the table

- `<tbody>` for the body

- `<tfoot>` for the foot

## Objects Constructor Notation

- create new objects using constructor `new`

- instead of `name: shay,` inside the object we use `user.name = 'shay';` to assign properties to the object

- this allows us to use functions for the creation of objects and DRY out our code

- we can use this syntax to add or delete properties `user.premium = true;` or `delete user.visible;`

- `this` is very helpful shorthand for referring to your object inside of itself

- arrays are their own special type of object using index numbers instead of variables

- built in objects are objects hard coded into JS or your webbrowser

- this is what allows DOM to function

