# Day 4 - AUDIO / VIDEO TAGS AND REVIEW

## Daily Journal
Eyyy look at that!

A whole challenge with no major setbacks or untold errors!
You gotta imagine that's a step in the right direction.  The MVC template remains incredibly valuable for debugging a project.  Cuz, to be sure, we had plenty of errors.  But all of those errors were easily trackable to their root document, and 90% of them always boiled down to simple errors that were fixable in a single line.

All of these challenges collectively offer a complete template for how to handle all the basics of the MVC pattern, and I will continue to refer back to them whenever I encounter an unusual error.

So here's hoping that tomorrow's checkpoint will go as smoothly as today's challenge did!

## Daily Challenges

Morning: 
``` JS
function timeConvert(time) {
  if (time < 60) {
    return time + " Minutes"
  } else {
    let hours = Math.floor(time / 60)
    let minutes = time - (hours * 60)
    return hours + " Hours: " + minutes + " Minutes"
  }
}
timeConvert(134)
```

Afternoon: Partner Challenge: https://github.com/ThomasSwisher/music-is-fun

### Read *Asynchronous Code > What is REST*

1. What does REST stand for, and in simple terms what does it mean?
    -Representational State Transfer

2. What does Stateless mean?
    -As we no doubt learned from the 90's classic "The Terminal" , Stateless means the server does not recognize the user of a particular API

3. What URL pattern is used when writing a RESTful API?
    -It must feature a User Identifier unique to each individual user, like a unique UserName, embedded in the URL