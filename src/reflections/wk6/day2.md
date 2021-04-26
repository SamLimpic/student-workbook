# Day 2 - VUE COMPONENT ARCHITECTURE

## Daily Journal
Oh dear... oh dear...

I thought yesterday was too good to be true...

What in the everloving *%@$ is a prop and why do they hate me?

I've done these readings, I've watched the videos, and their purpose on a functional level is completely beyond me...

Not only that, but even when I use them exactly as it seems I should, they simply decide to not do what I ask them to...

Were they originally in the wrong component?  Absolutely.  Did they work any better after I put them in the right one?  Hardly.

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

Afternoon: https://github.com/SamLimpic/spellbook-vue

### Read *Frontend Frameworks with Vue3 > How to use Props in Vue*
1. What are props?
A means to pass variables and other information around between different components, like arguments to a function

2. What are props used for?
To pass values from one component to another, reducing the need to redefine values over multiple components.

3. Where can props be used or accessed?
Man... I honestly still have no idea.
Components?  Templates?  Functions?  All of the above?
