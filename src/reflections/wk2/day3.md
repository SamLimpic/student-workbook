# Day 3- INTERACTING WITH THE DOM AND EVENTS

## Daily Journal

I really find this aspect of Javascript to be really interesting.  It's cool to be able to dynamically generate HTML aspects on the page based on variables, and it allows a page a lot of leeway in design.  There are plenty of projects I've worked on that utilize dynamically generated HTML to a point, but this lesson really helped me see how far that concept can be pushed to facilitate a lot of functionality.  The idea of utilizing backticks to directly interpolate and reference variables has a lot of application that I can see being very useful in most any project I will be working on, and I intend to make use of it as much as possible to reduce the amount of hard HTML that must go into any page.

## Daily Challenges

Morning:
``` JS
function evenOrOdd() {
    if (num % 2 == 0) {
        console.log("even")
    }   else {
        console.log("odd")
    }
}
```

Afternoon: https://github.com/SamLimpic/super-fight

### Read *Intro to JS > Chrome Developer Tools*

1. What are the main ways to write information to the console? Why/when should you use each style.
    Printing to the console with "console.log()" can help you verify if a function is working or a value is calculated properly.
    Printing errors to the console with "console.error('error message') can help you identify a particular error in your function, with a following link that will help you identify the area where the error is occurring.

2. Which tab allows you to see the breakdown of HTML/CSS and how can this tab be useful when debugging HTML?
    The Elements tab shows your HTML and CSS breakdown, as well as edit it and see live changes on the web page.

3. Outside of writing everything to the console, what is a better way to debug your code?
    Using the Debugging pane in the Sources tab, you can view your call stack and breakpoints.