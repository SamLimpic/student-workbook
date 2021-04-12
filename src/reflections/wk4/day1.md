# Day 1 - INTRO TO ASYNCHRONOUS CODE

## Daily Journal
I have been waiting for this for ages and I didn't even realize it!

I've heard about calling to servers to get information, but I had no idea how the technical process was achieved.  But utilizing APIs makes a lot of sense.  There have been plenty of projects I've worked on where I've simply hard-coded information that I knew was readily available, because I had no idea how to get that data in a usable form dynamically.

Turns out, the DnD 5e Players Handbook exists as an entire API, and the me of 2 months ago cries in frustration as I look at the hard-coded classlist that currently takes up 300 lines of Javascript in an old project...

## Daily Challenges

Morning: Checkpoint III Review: 

Afternoon: https://github.com/SamLimpic/bad-trivia

### Read *Asynchronous Code > Callback Hell*

1. What are some of the signs and causes of Callback Hell?
    -Bloated code that tries to do too much with a single function
    -Lack of modules that encapsulate aspects of your code to be referenced
    -Ignoring small errors, which build upon one another

2. What does the asynchronous mean and how are callbacks involved?
    -"Happens in the future, not immediately"
    -Callbacks await a "signal" to fire a specific function only when it is needed

3. Summarize the 3 ways to avoid / fix Callback Hell
    -Simplify your code
    -Implement models / modules to encapsulate your code
    -Fix every error, large or small