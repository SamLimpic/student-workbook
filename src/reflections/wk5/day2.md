# Day 2 - USING AN ORM TO INTERACT WITH A DATABASE

## Daily Journal


## Daily Challenges

Morning: https://github.com/SamLimpic/node-day-1 (updated)

Afternoon: 

### Read * Servers with Node/Express > MongoDb Relationships*

1. What are the three types of relationships?
    -One-to-One (1:1)
    -One-to-Many (1:N)
    -Many-to-Many (N:M)

2. What are the benefits of the traditional linking of relationships instead of Embedding
    -Linking in a One-to-Many relationship results in individually getting each data point rather than getting them all at once, which reduces the server load for smaller data sets.  Though it does increase server load with large ones.

3. What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
    -The independent relationships that each side of the Many-to-Many relationship has will be a large factor in determining how to best establish it in your server.  You'll want to consider efficient means of getting all data sets that exist between the pair, and how those data sets are retrieved by them in the first place.