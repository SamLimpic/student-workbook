# Day 4 - WORKING WITH MVC WITH COMPLEX DATA, ARRAY METHODS

## Daily Journal
Aaand we're back.  Today hurt my head.

MVC is starting to flow better in my brain, but it's still such a foreign concept, splitting code across 4 documents.  The pattern makes sense, and I completely understand the methodology behind this template.  That said, I do feel I'm beginning to wrap my head around the syntax of it a bit more.

The partner challenge was a fun one!
It was really nice to be able to scrap code together from the week's earlier challenges and combine them all into a cohesive whole!  It certainly bodes well for what this week's checkpoint will offer.

With any luck, I'll be able to save some legwork of the hefier coding by relying on our past projects as a framework.  I can definitely see why having a comprehensive portfolio is incredibly valuable!

## Daily Challenges

Morning: 

Afternoon: (partner github) https://github.com/davidparker83686/sporting_goods

### Read *Advancing with JS > The Observer Pattern*

1. What problems does the Observer Pattern seek to solve?
By abstracting your code into a series of breakpoints with reusable references, you can exponentially increase the flexibility and reusability of a design with a minimal amount of code.

2. What are the three mechanisms of the observer pattern?
The Subscribe Method, the Unsubscribe Method, and the Broadcast method.

3. Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
You can set an observer to watch a Proxy Object for changes, and then trigger a complex function when that Object changes, and only when it changes.  This cuts down on the amount of raw code you need to trigger such an event, and allows for inumerable instances of that function trigger, so long as you can trigger the watcher to run that function.