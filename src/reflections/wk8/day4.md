# Day 4 - CAPSTONES

## Daily Journal

Day 4!

Oh we're doing good...

Questions: finalized.
Server: finalized.
API: begrudgingly mined.

From here, we're splitting in two again. Kevin and I are handling front-end page architecture, ensuring cohesion across all our Vue components and pages.
Veronica and Gwen are verifying that our data paths can pull the information that we need, and ensuring that these paths are consistent across multiple API queries.

As you might expect, it is that latter point that is giving us trouble. Wizards have to be full of just the boomeriest boomers that ever boomered, and it's reflective in the information they _allowed_ to be accessible via the API. I do not doubt that, if a more comprehensive API were able to me made, it would have been already. I can only assume that Wizards do not _want_ a comprehensive API, as they feel it would eat into the profits of their printed books.

I bristle at this notion, really. Our app is designed to bring people to the game that _would have never played otherwise_. If we had our way, we could condense the entire PHB into this program and draft up a ready-to-play character at any level. The person that made that character would then have an incentive to _buy their damn books_ where they would have had no interest in doing so before we came along. They truly have no concept of how their digital limitations kneecap any potential future markets that are hoping to embrace a digital platform.

So... Screw that. I'm just gonna do it myself.

## Daily Challenges

Morning: Capstone

Afternoon: Capstone

### Read "Working In a Professional Environment > Testing in Vue"

1. What are the three main types of testing we can accomplish in Vue? What does each method provide?
   Unit Testing: testing individual units of code in isolation.
   Component Testing: testing how individual units interact when combined into a single component.
   End-To-End Testing: testing the amalgamation of interactions between your units, components, and pages.

2. What testing method do you think is the most useful? Why?
   It seems that each method has a place within the development process. Ideally, you'd use each in tandem to ensure functionality from the ground up.

3. What testing method do you think is the least useful? Why?
   Of the three, I'd say that End-to-End testing shows the most redundancy. If you can verify that your units work in isolation, and that they work when combined into components, there isn't much reason to suspect they wouldn't work when combined further.
