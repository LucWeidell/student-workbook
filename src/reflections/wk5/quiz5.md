# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
Create, Read, Update, Delete
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
C: Post
R: Get
U: put
D: Delete
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
ORM: Object-Relational mapping:
We use NodeJS to read what mongoose returns to us from MongoDB
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
Post, Put
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
Asynchronous
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
mongoose/Mongoose
mongoose
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware is anything that is created in between the exit responce for a request.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks.
<!-- enter you answer in the space below -->
```
Request / Response
```
**9.**
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
await api.get('?winter')
You can also add the params field in axios too
```