# Error Handling and Debugging

[Back to Main Page](README.md)

An important part of writing code is knowing how to resolve errors

- it's important to keep in mind the order code is on a page, an issue higher up the page can break code lower down

- keep in mind both variables and code will either by exclusive to their function or a global variable

- one line of code is processed at a time

- before a script is executed it is first prepared by creating variables and confirming this keywords

- when code is executed it assigns value to the variables then executes the statements

- whenever possible create variables inside the function they are being used inside of

- if an error is generated, the interpreter looks for exception-handling or error handling instructions

- you can debug script to prevent errors but it's good practice to set error-handling statements for unexpected scenarios

## Debug Workflow

### Where's the Problem

1. Review the error message in console for type and location

1. check how far the code ran

1. Use breakpoints where things are going wrong to go through it piece by piece

### What's the Problem

1. Check to see if vars have expected values

1. test smaller pieces of the code

1. check parameters for a function or numbers in an array

## What We Learned

- debugging is how we find errors

- use the console to narrow down the location of the area

- if you know you may get an error you can account for that using `try,catch, finally`