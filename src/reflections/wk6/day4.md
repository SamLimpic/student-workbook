# Day 4 - USING AUTH0 IN VUEJS AND REVUE ADVANCED FRONTEND FRAMEWORKS

## Daily Journal
I don't know who you are. I don't know what you want. If you are looking for ransom, I can tell you I don't have money.
But what I do have are a very particular set of skills; skills I have acquired over a very long 6 weeks. Skills that make me a nightmare for people like you.
If you fix this blog post now, that'll be the end of it. I will not look for you, I will not pursue you.
But if you don't, I will look for you, I will find you, and I will kill you.

I swear, spending 3 hours trying to figure out why my app is crashing, essentially rewriting it from the ground up, only to realize that it was all because ONE %*#(@&) GUY somehow uploaded a blog entry without a Creator Id is a pain I would only wish on THAT ONE GUY.

## Daily Challenges

Morning: 
``` JS
function findTheVowels(str) {
  let newStr = ""
  for(let i = 0; i < str.length; i++>) {
    if (str[i] == 'a' || str[i] == 'e' || str[i] == 'i' || str[i] == 'o' || str[i] == 'u') {
      newStr += str[i]
    }
  }
  return newStr
}
```

Afternoon: https://github.com/SamLimpic/bloggr-vue

### Read *Frontend Frameworks with Vue3 > Using Nested Routes in Vue.js*

1. What is a nested route?
A means to nest a component inside another component, and render hem without causing issues

2. When might you use a nested route? (other than the provided example)
If you needed to add a component inside another component if a certain variable is rendered, but otherwise leave it out... I think?

3. Can you pass parameters through nested routes? When might you use them?
Yes, when you want to dynamically render a component based on a variable referenced in the parent component
