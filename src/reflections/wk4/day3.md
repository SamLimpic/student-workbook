# Day 3 - WORKING WITH MULTIPLE APIS

## Daily Journal
Oof.  Biiig oof today...

That's what I get for getting cocky.  I got super excited to try out all these weird APIs and do fun stuff with them, and thus rushed my setup.  By the time 5pm rolled around, I had all my weird functionality working exactly how I wanted!  I had a team builder function, I had stats generated, and I had a layout I was perfectly satisfied with!

Then I hit delete... and everything crashed.
Errors throwing all over the place, and I have no idea what t.replace is supposed to mean?!
And of course, I put off core functionality until the end of day, so there's nobody around to solve what ended up being an incredibly trivial problem.  Turns out, I had doubled up on my "add active" function for both APIs, effectively calling the same function for two different sets of data.  At the time, it didn't seem like it would hinder my functionality, and it didn't seem to affect any other part of my code, so I didn't even realize it would be such a problem!

Of course, after heading home in frustration, I'm describing the problem to my dear beloved rubber ducky of a wife, and I immediately realize the mistake.  5 minutes, and a second (incredibly similar) draw function later, and the whole things works like a charm!

So let that be a lesson, I guess... Small shortcuts lead to big headaches.

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

Afternoon: https://github.com/SamLimpic/pokemen

### Read *Asynchronous Code > Async*

1. What is the purpose of Async/Await?
  -To return promises in a manner that makes your code look synchronous, when it is in fact asynchronous

2. What must you do in order to await a promise inside of a function?
  -You must define your function as "async"

3. What are some of the primary benefits of Async/Await?
  -You can chain async functions, simplify your code, and make debugging easier