# Day 3 - FORMS AND TEMPLATES

## Daily Journal
Kind of a straightforward lesson today, for once!

It was definitely good to get a refresher on such a core component of dynamic web design, but it was also nice to have a lesson that was at least familiar from the outset.

Today's challenge was a fun one too!  I'm a bit disappointed I didn't have the time to really flesh out the design of it beside the base functionality, since it has a lot of potential for a fun page!  I'll just have to cannibalize the code later for a bigger project.

## Daily Challenges

Morning: 
function isPalindrome(str) {
let noSpace = (str.split(" ").join("")).toLowerCase()
for(let i = 0; i < Math.floor(noSpace.length / 2); i++) {
  if (noSpace[i] == noSpace[noSpace.length-(i+1)]) {
  } else {
    return false
  } 
}
return true
}
isPalindrome("aibohphobia")

Afternoon: https://github.com/SamLimpic/grugs-list

### Read *Advancing with JS > An Intro to Javascript Proxy Objects*

1. What are the two common operations that will set in the handler?
You use "get" and "set" in the handler

2. What do you have to make sure you are doing with every "Get" to ensure the value does not become "undefined?"
Ensure that the "observer" is triggered by referencing the value you are trying to modify and setting it to equal itself.

3. What are some of the benefits of the proxy objecy that we are using in our structure for applications?
Proxy objects allow us to manipulate the data of an object freely in our code, without changing the properties of the function itself.  This is incredibly useful for complex functions that require that data be manipulated, but also need the object to have its base values remain intact as a reference.
