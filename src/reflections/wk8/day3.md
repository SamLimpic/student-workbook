# Day 3 - CAPSTONES

## Daily Journal

Day 3!!

Oh boy have we made moves!

We have our Quiz sorted out, or at least a rough draft! It will consistently and reliably deliver you a suggested character class that fits your answers, and we have already decided on the recommended Races and Backgrounds for each Class! (Under the hood, we need to call "Classes" "Jobs" for obvious reasons, and it bothers me on a spiritual level).

Next we're moving on to Back End architecture, on one hand, and diving into the DnD API on the other! We're splitting into two teams, with Veronica and Kevin taking point on building our Server logic, and Gwen and I are taking the DnD API head on!

I can already tell this API is gonna be a nightmare to sift through. And given that we already know that my _personal_ stretch goal will require hard-coding elements not found in the API, I am very tempted to simply hard code everything we need before getting too far along in the project...

I'm afraid that if we hold off too long, we'll hit a wall once our MVP is done that won't be able to be overcome without hours of hard-coding, and nothing to do in the meantime...

## Daily Challenges

Morning: Capstone

Afternoon: Capstone

### Read "Working In a Professional Environment > Unit Testing"

1. What is Software Development Testing?
   Breaking your code down into the smallest functional "units" and testing each of those individually to ensure their functionality.

2. What are the benefits of Testing in software development?
   Testing your units individually ensures that they work in a vacuum. Thus, when they inevitably interact, you can assume that the reason for unexpected errors is due to _that interaction_ rather than the base functionality of the interacting parts.

3. What are some potential drawbacks of Testing in software development?
   This can sometimes give you a false sense of confidence in your individual units. However, it is possible that your tests are flawed, and are not testing the exact aspect of that unit that is being called upon. Therefore, you could have a unit that passes _a_ test, but still fails when implemented. This will lead you to believe that the component is not at fault, but the interaction. When in actuality, the component was not being tested properly to begin with.
