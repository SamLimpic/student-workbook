# Day 1 - INTRO TO JAVASCRIPT

## Daily Journal


## Daily Challenges

Morning: 

Afternoon: 

### Read *Intro to Javascript > var, let, and const*

1. What is Scope?
    Scope is the area that a variable is available for use.  A variable declared within a function would have "local scope" whereas a variable declared outside of a function would have "global scope".

2. What is Hoisting?
    Hoisting is a mechanism where variables are moved to the top of their scope prior to execution, regardless of their placement within a function.  This can cause problems when using var in your declaration, as your variable could be overwritten multiple times which are at odds with the intent of your function.

3. In what cases might you use let vs const vs var?
    Let is preferred for base variable declaration, as it is block scoped exclusively to the function it is declared in.  Unlike var, a let variable cannot be re-declared within its block scope.
    Const declares variables with constant values, and is also block scoped.  And unlike let, a const variable cannot be updated or re-declared, regardless of where that redeclaration would appear.
    Var seems to be on its way out in the developer sphere, as it tends to cause unnecessary problems in complex code that let or const do not have to deal with.