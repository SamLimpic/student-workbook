# Day 3 - WORKING WITH MULTIPLE APIS

## Daily Journal


## Daily Challenges

Morning: 
``` JS
function factorize(n) {
  let factorArr = []
  for (let i = 1; i <= n; i++) {
  if (n % i == 0) {
    factorArr.push(i)
  }
  }
  if (factorArr.length == 2) {
    return "Prime Number"
  } else {
    return factorArr
  }
}

factorize(16)
```

Afternoon: 

### Read *Asynchronous Code > Async*

1. What is the purpose of Async/Await?
  -To return promises in a manner that makes your code look synchronous, when it is in fact asynchronous

2. What must you do in order to await a promise inside of a function?
  -You must define your function as "async"

3. What are some of the primary benefits of Async/Await?
  -You can chain async functions, simplify your code, and make debugging easier