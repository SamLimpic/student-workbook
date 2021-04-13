# Day 1 - INTRO TO NODEJS

## Daily Journal
Welp... node is starting off with a lot of Greek.

Though at this point, that seems pretty standard.

I feel like these weeks fall into a bit of a pattern: Monday, we are acquainted with the terminology and get accustomed to copy / paste jobs to get our code functional.  I imagine that by Wednesday, this pattern will look more French than Greek, and I took a bit of French in High School so I should be able to sound out a few of those words by then.  By then, too, I'd imagine the copy / paste jobs will be either much more competently implemented or else dropped altogether.

Let's see.

## Daily Challenges

Morning: Checkpoint IV Review: 

Afternoon: https://github.com/SamLimpic/node-day-1

### Read *Servers with Node/Express > Using Query Parameters*

1. What is the purpose of a Query String?
    -A Query String appends information to the end of a server URL to access specific data at the endpoing that the QS specifies.

2. What is the format of a query parameter? How does it start? How do you distinguish between one parameter and the next?
    -A Query Parameter such as "?a=1&b=2" would be translated by Express as "{ a: '1', b: '2' }", so the ? identifies the start of the query, and the & signifies the separation of the 2 parameters

3. When do you think Query parameters would be helpful when writing your server?
    -A shorthand for quickly posting / getting specific information, objects, or values to / from the server