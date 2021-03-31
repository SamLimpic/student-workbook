# Day 2 - ENCAPSULATION

## Daily Journal
This one was a bit of a headache...
The analogy we were given at the start of class was that base Javascript was essentially "teaching you how to drive a car" and that MVCS was meant to pull the hood back and show us "how the car works."  It seemed an appropriate analogy, especially because I have no clue what's under the hood of my car!  Don't get me wrong, I get the principle of the whole thing: gas burns, goes boom, makes engine go vroom.  Wheels turn, and brakes function, hydrolically.  Transmission... works.  I get it more or less.
Unfortunately, it's probably gonna take a little more time to fully grasp all the minute details that go into what makes our MVCS template work the same way as base Javascript.
I'm definitely getting there, but for the moment it feels like a 2 steps forward and 1 step back situation.  Code that I could confidently write in an hour last week took me closer to 3 to make work the same way today.
Still, I can easily see the usefulness of building this code in such a way: every time it threw an error (many times) it directed me to the exact point in my framework where the code ceased to function properly, which provided a roadmap to solve the problem!

## Daily Challenges

Morning: 

Afternoon: https://github.com/SamLimpic/vending-machine

### Read *Advancing with JS > Encapsulation in JavaScript*

1. What is the purpose of "encapsulation?"
Sequester your code into compartmentalized sections designed to accomplish a single objective.  This makes design and troubleshooting much easier for both the developer and any other developers who need to dissect the code later.

2. What were some of the problems with closures and the underscore prefix?
They make a function "private," so it is inaccessible to the user.  This can be problematic if it is implemented incorrectly, and key functions are hidden behind a wall.

3. How do we create private variables in a ES6 Class? Why would you do this?
Create a model that is only referenced in the main.js file through encapsulation.  This is ideal if a variable is meant to be unchangeable to a user who could otherwise manipulate the values to undermine the functionality of the code.