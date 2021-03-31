# Day 3 - FORMS AND TEMPLATES

## Daily Journal


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

Afternoon: 

### Read *Advancing with JS > An Intro to Javascript Proxy Objects*

1. What are the two common operations that will set in the handler?

2. What do you have to make sure you are doing with every "Get" to ensure the value does not become "undefined?"

3. What are some of the benefits of the proxy objecy that we are using in our structure for applications?
Proxy objects allow us to manipulate the data of an object freely in our code, without changing the properties of the function itself.  This is incredibly useful for complex functions that require that data be manipulated, but also need the object to have its base values remain intact as a reference.