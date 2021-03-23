# Day 2 - JAVASCRIPT FUNCTIONS, OBJECTS, AND LOOPS

## Daily Journal
Loops!
All the loops!
Loops on loops, loops in loops, loops from loops!
When I got here I had a for loop figured out pretty well.  I used it for basically anything requiring iteration, and never really bothered with its specific variations.  But, after today's challenge it's incredibly clear to me how useful those variations are.  Not only do they simplify your code in the line, they also implicitly tell the user what they are meant to accomplish, without the user having to delve inside every for loop on your page to dig out its true purpose.
After today's excercise, I can think of a number of independent projects that I ought to revise with an appropriately specific loop, rather than spreading generic for loops across all my code.

## Daily Challenges

Morning: 

Afternoon: https://github.com/SamLimpic/js-tests-loops-and-arrays

### Read *Functions, Objects, and Control Flow*

1. What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?
    Function Declaration: defines a named function
        function name(parameters) {}
    Function Expression defines a named or anonymous function
        let name = function(parameters) {}
    Arrow Function: a truncated syntax for writing Function Expressions

2. What is the difference between Parameters and Arguments?
    Parameters are used when defining a funciton; they are the names created in the function definition.
    Arguments are the values the function receives from each parameter when the function is executed.

3. What are higher order functions? Can you provide an example?
    Higher Order functions accept another function as a parameter or returns another function, such as "array.prototype.filter".