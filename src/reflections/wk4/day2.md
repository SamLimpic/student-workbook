# Day 2 - HTTP REQUESTS CONTINUED

## Daily Journal


## Daily Challenges

Morning: 
```js
function mostCommonLetter(str) {
    let letters = {}
    let max = 0
    let mostCommon = ''
    for(let i = 0; i < str.length; i++) {
        let char = str[i]
        letters[char] = letters[char] || 0
        letters[char]++
        if(letters[char] > max) {
            max = letters[char]
            mostCommon = char
        }
    }
    return mostCommon
}
```

Afternoon: 

### Read *Asynchronous Code > JavaScript Promises*

1. What are the three states of a Promise?
    -Pending, Resolved, and Rejected

2. How do promises seek to resolve the issues of "callback hell"?
    -By attaching callbacks to Promises, you simplify your code and reduce the potential of plunging into "callback hell"

3. What is the difference between .then() and .catch()?
    -.then() is called after a Promise is resolved
    -.cath() is called after a Promise is rejected