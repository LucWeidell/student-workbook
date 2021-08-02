# USING AN ORM TO INTERACT WITH A DATABASE  (Day 2/5)

## What are the three types of relationships?
One to One,
One to Many,
Many to Many

## What are the benefits of the traditional linking of relationships instead of Embedding
Relationships allow you to still find data between the relationship without having to
duplicate the data between the too. Helps follow encapsulation and decoupling as well.

## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
Many to many relationships should have a middle ware between them. This helps you to determine what
info should be shared during a certain instance. Otherwise it is very hard to conceptualize many, many to many
relationships at once.

## Afternoon Project
https://github.com/LucWeidell/creglist-db-1