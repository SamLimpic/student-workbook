# Day 4 - AUDIO / VIDEO TAGS AND REVIEW

## Daily Journal


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

Afternoon: 

### Read *Asynchronous Code > What is REST*

1. What does REST stand for, and in simple terms what does it mean?
    -Representational State Transfer

2. What does Stateless mean?
    -As we no doubt learned from the 90's classic "The Terminal" , Stateless means the server does not recognize the user of a particular API

3. What URL pattern is used when writing a RESTful API?
    -It must feature a User Identifier unique to each individual user, like a unique UserName, embedded in the URL