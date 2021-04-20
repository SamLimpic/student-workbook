# Day 2 - VUE COMPONENT ARCHITECTURE

## Daily Journal


## Daily Challenges

Morning: 
``` JS
function repeaterCode(arr) {
  let out = ''
  for(let col = 0; col < arr[0].length; col++) { 
    let seen = {}
    let highestCount = 0
    let highesLetter = ''
    for(let row = 0; row < arr.length; row++) {
      let char = arr[row][col]
      seen[char] = seen[char] || 0
      seen[char]++
      if (seen[char] > highestCount) {
        highestLetter = char
        highestCount = seen[char]
      }
    }
    out += highestLetter
  }
  return out
}
```

Afternoon: 

### Read *Frontend Frameworks with Vue3 > How to use Props in Vue*
1. What are props?

2. What are props used for?

3. Where can props be used or accessed?
