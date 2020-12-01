# HTML CSS & JS Basics

[Back to Main Page](README.md)

## Tags

### Structure

- headers `<h1>,<h2>`

- paragraphs `<p>`

- bold `<b>` and italics `<i>`

- use `<p>` or `<br>` to create white space vertically

- use `<hr />` to create white space horizontally

### Semantic

- `<strong>` conveys importance

- `<em>` for emphasis

- `<blockquote>` for big quotes

- `<q>` for small quotes

- `<abbr>` abbreviates

- `<cite>` to reference and external source

- `<address>` to indicate an address

## [Intro to CSS](css.md)

- try to think of everything as tiny boxes surrounding individual pieces of content

### Selectors

- Universal `* {}` applies to all elements on a page

- Type matches specific element names `p, li {}`

- Class only targets attributes with the same class attribute `p.thing{}`

- ID matches a specific ID 

- Child matches elements that are children of other specific elements `head>h2 {}`

- Descendant targets an element that sits inside the first 

- Adjacent sibling targets the first specified element after the original

- General Sibling targets any element of the appropriate type after the first

## [Basic Javascript](program-java.md)

### Arrays

- store a list of variables

- `let things = ['tray', 'phone', 'light'];`

- values are accessed like a numbered list starting with 0

- `things.item(1);` returns `phone`

- changing values requires calling the specific item in the array

- `things[2] = 'apple';`

### Expressions 

- force results into a single value

- value can be assigned or determined by an operation

### Operators

- only string operator is `+` for concatination

- typical arithmetic indicators for add, subtract, divide and multiply

- `++` increase value by 1

- `--` reduce value by 1 

- `%` divides 2 values and returns remainder

## [Decisions and Loops](decisions.md)

### Conditional Statements

1. A statement a is checked and returns a value true or false

1. The statement then indicates what to do given the result

### If...Else Statements

- use these to check if a given thing is true or false

- indicate instructions on how to process based on the result

