# MYSQL RELATIONSHIPS

## What is the difference between a primary key and a foreign key
PK: unique itendifier for an item on a table
FK: Itendifier for a relationship with an item on another table.

## What is an Alias?
Alias is rename a property on the table or rename a table can be doen with AS or
just a banana word after a table.

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:
Select
p.*
d.*
From doctors d
Join patients p ON d.patientId = p.id