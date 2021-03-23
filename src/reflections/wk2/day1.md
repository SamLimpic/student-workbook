# Day 1 - INTRO TO JAVASCRIPT

## Daily Journal
And we've arrived at Javascript!

I am unironically excited, as Javascript is by far the most engaging language I've experienced so far.  It is the first language I've really felt capable of achieving legitimate products with, and using it as a problem solving tool is incredibly satisfying.
We went over most of the basics today, including Switch statements.  And I actually understood Switch statements for the first time!  While working though my own independent study, Switch statements always eluded me, and I couldn't quite determine how to make them suit my needs.
Turns out, after listening to a thorough explanation, I incorporated a Switch statement into one of my independent projects and solved a problem I'd been struggling with for weeks!  Huzzah!

## Daily Challenges

Morning: 

Afternoon: https://github.com/SamLimpic/js-tests-basics

### Read *Intro to Javascript > var, let, and const*

1. What is Scope?
    Scope is the area that a variable is available for use.  A variable declared within a function would have "local scope" whereas a variable declared outside of a function would have "global scope".

2. What is Hoisting?
    Hoisting is a mechanism where variables are moved to the top of their scope prior to execution, regardless of their placement within a function.  This can cause problems when using var in your declaration, as your variable could be overwritten multiple times which are at odds with the intent of your function.

3. In what cases might you use let vs const vs var?
    Let is preferred for base variable declaration, as it is block scoped exclusively to the function it is declared in.  Unlike var, a let variable cannot be re-declared within its block scope.
    Const declares variables with constant values, and is also block scoped.  And unlike let, a const variable cannot be updated or re-declared, regardless of where that redeclaration would appear.
    Var seems to be on its way out in the developer sphere, as it tends to cause unnecessary problems in complex code that let or const do not have to deal with.