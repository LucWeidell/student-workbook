# AUDIO/VIDEO TAGS AND REVIEW (Day 4/4)

## What does REST stand for, and in simple terms what does it mean?
Rest = Representational State Transfer
A set of constraints tied to an api to expose and manipulate controlled exposed object information
Use Case: When called the "server" (or requested source") will pass the client "requestor" a representation of data wanted.
<!-- NOTE IMPORTANT -->
***** client and server: DO NOT mean only literal client and server. The DATABASE CAN BE THE CLIENT.
its just who is the requestor and who is the provider
<!-- SECTION IMPORTANT -->

## What does Stateless mean?

## What URL pattern is used when writing a RESTful API?
Typical order:
  1 The url with the identifier of the resource to interact with
  2 The required information to complete the request:
      (ex: a post must provide an POJO or the Data strucutre to be added)
      (ex 2: getter should have url id, but no POJO since its just requesting info back)
  3 IT NEEDS TO FOLLOW the RESTful constraints of the source api.

## Afternoon Challenge (this was solid):
https://github.com/TimothyKimble/Music-Is-Fun