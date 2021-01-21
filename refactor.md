# Refactoring

[Back to Main Page](README.md)

functional programming is a system used in writing code to maintain systems in such a way that provides more structure and reliability and treats computation as math functions

## Purity

- returns the same results given the same paraments

- does not have any observable side effects

- any time a global object that is not passed into the function as a parameter the function would not have purity

- if a function reads external files it's not pure

- RNG cannot be a pure function

- observable side effects include modifying a global object or a parameter passed by reference

- the goal is to isolate each function so as to not impact other parts of a system

- this makes it much easier to test our code

## Immutability

- aka unchanging over time or unable to be changed

- instead you create a new object with a new value

