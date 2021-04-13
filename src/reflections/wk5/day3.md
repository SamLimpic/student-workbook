# Day 3 - RELATIONSHIPS

## Daily Journal


## Daily Challenges

Morning: Checkpoint IV Review: 

Afternoon: 

### Read *Servers with Node/Express > Mongoose 101: Working with Subdocuments*

1. In simple terms what is a sub-document?
    -Documents that are nested inside other documents

2. When might you use a sub-document?
    -When you're looking to create a document that has multiple child properties associated with a single parent property.  These would be nested inside the parent as a sub-document object with its own properties

3. How do you add to a collection of sub-documents? What about editing them?
    -Create a base object with no sub-documents, then edit it to add a series of sub-documents.  Running save will then generate a single document with its nested sub-documents.