# Day 1 - JAVASCRIPT CLASSES

## Daily Journal
This is yet again a lesson that I wish I had last week!
My checkpoint features a large number of object arrays, each with their own unique stats and values to be drawn into various functions.  It sure would have been nice if I'd been able to build out Classes for those objects, and use that layout to clean up my declarations at the start of my app.js file.
Obviously, that relies heavily on "onclick" functions, which I understand can cause conflict if I were to import those classes from a model.  But even just declaring the classes at the start of the function would have cleared around 50 to 100 lines from my code!

## Daily Challenges

Morning: Checkpoint II Review: https://github.com/SamLimpic/dungeon-miner

Afternoon: https://github.com/SamLimpic/zoo-keeper

### Read *Advancing with JS > ES6 modules*

1. What problem does using exports solve?
Exports clean up space in your main app.js file but storing reusable variables in a secondary .js file, then pulling only the variables when they are called

2. How does "export" differ from "export default?"
"Export default" exports the given object as the "default" value when the model is imported

3. What is a benefit of using the "Module System?"
You can split your code into smaller, self-contained pieces; and you can concatenate multiple scripts together.
Both of these clean up your base app.js file and improve functionality, as well as debugging.