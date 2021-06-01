# Day 2 - MYSQL RELATIONSHIPS (MANY-TO-MANY)

## Daily Journal

This is kind of a weird one...

I get that we're meant to be working on Many-to-Many relationships, but I couldn't help but think about the project we worked on last week, involving Recipes and Ingredients (or in my case, Spells and Components).

I remember running into trouble with that project, since I had built it thinking we would have single ingredients represented in multiple recipes. Needless to say, that proved rather difficult, as SQL doesn't manage MTM relationships through sub-documents, but sub-tables.

In the end, I needed to built each Ingredient with the Id of the Recipe that it was tied to, which didn't sit well with me as it was very limited.

So today, I rebuilt that program with MTM relationships in mind, and Lo and Behold the whole thing worked exactly how I thought it should have from the beginning! I might even pull some bits of that for The Tavern...

## Daily Challenges

Morning:

Afternoon: https://github.com/SamLimpic/cs-all-spell

### Read "Dotnet WebAPI's > Relationships"

1. What is the difference between a primary key and a foreign key
   Primary Keys are used to identify the item they are a property of, as a means to differentiate them from the other items in a table.
   Foreign Keys are used to reference a related property from another item in another table.

2. What is an Alias?
   A means to condense your SQL statements by abbreviating the variable name with a single character as a reference point.

3. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

CREATE TABLE doctors (
id INT NOT NULL AUTO_INCREMENT,
-- CODE OMITTED
PRIMARY KEY (id)
)

CREATE TABLE patients (
id INT NOT NULL AUTO_INCREMENT,
-- CODE OMITTED
PRIMARY KEY (id)
)

CREATE TABLE doctors (
id INT NOT NULL AUTO_INCREMENT,
doctorId INT NOT NULL,
patientId INT NOT NULL,

FOREIGN KEY (doctorId)
REFERENCES doctors(id),
FOREIGN KEY (patientId)
REFERENCES patients(id),
)

SELECT
p._,
d._
FROM patients p
JOIN doctors d ON p.doctorId = d.id
WHERE
p.id = @id
