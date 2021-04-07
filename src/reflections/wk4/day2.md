# Day 2 - HTTP REQUESTS CONTINUED

## Daily Journal
Oh I like APIs...

I still can't get over how easy it is to just... get all of it.

I spent so much time hard coding data, knowing the entire time that there was a better method that I simply didn't know how to do...  I feel like the Internet has been invented all over again!  I've been snooping around and have found the DnD 5e API, which contains every race / class breakdown in the book, as well as spells, backgrounds, and equipment!

I feel a scheme coming on...
Seems like it wouldn't be terribly difficult to implement that API into a character-building app...
I've actually had this idea for a while but was unsure how to deal with the massive amount of data I'd need to make it function properly...  I think that's handled now.


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

Afternoon: https://github.com/SamLimpic/gregs-list-api

### Read *Asynchronous Code > JavaScript Promises*

1. What are the three states of a Promise?
    -Pending, Resolved, and Rejected

2. How do promises seek to resolve the issues of "callback hell"?
    -By attaching callbacks to Promises, you simplify your code and reduce the potential of plunging into "callback hell"

3. What is the difference between .then() and .catch()?
    -.then() is called after a Promise is resolved
    -.cath() is called after a Promise is rejected