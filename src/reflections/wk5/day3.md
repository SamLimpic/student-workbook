# Day 3 - RELATIONSHIPS

## Daily Journal
Relationships actually made a lot of sense today!

Making a galactic API was pretty fun too!
I feel like having a resource of galaxies, stars, planets, moons, and species will come in handy for some nerdy projects down the way, so I was sure to map out the majority of our solar system, complete with photos!

And honestly, even if I'm not asked for a valid reason to utilize it this week, I'll make a point of retrofitting some project to fit my purposes...
Even something basic, like an index of our solar system, is a cool thought.  I'm sure I could track down an existing API and import what I needed for it, which would give me that much more data to work with, but there is something really satisfying about actually building one myself.

Hell, I'm pretty sure I could gut GregsList and make an index, and you could even add stuff in real time that I've yet to include, in-app!

## Daily Challenges

Morning: 
``` JS
function anagram (str, rts) {
  let a = str.split('').sort().join('').toLowerCase()
  let b = rts.split('').sort().join('').toLowerCase()
  if (a == b) {
    return true
  } else {
    return false
  }
}
```

Afternoon: https://github.com/SamLimpic/space-relations

### Read *Servers with Node/Express > Mongoose 101: Working with Subdocuments*

1. In simple terms what is a sub-document?
    -Documents that are nested inside other documents

2. When might you use a sub-document?
    -When you're looking to create a document that has multiple child properties associated with a single parent property.  These would be nested inside the parent as a sub-document object with its own properties

3. How do you add to a collection of sub-documents? What about editing them?
    -Create a base object with no sub-documents, then edit it to add a series of sub-documents.  Running save will then generate a single document with its nested sub-documents.