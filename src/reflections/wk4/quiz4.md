# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Asynchronous means that certain parts of code continue to operate and free themselves up for other tasks.
Synchronous means that all the code operates one after the other without delays or promises.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is a continuous running piece of code that waits for a particular trigger event.
Such as a changing state of a variable or for a key event to be triggered through an action.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open–closed principle: a key principle of encapsulation and maintaining modularity
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
Higher order functions we are usually working with are the array methods. Its were the function is an assister to other data,
such as forEach has a lambda is contained within for each element.

```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
Promise is what is left after an await api call from axios. Promises are captured in a
try catch statement if it didnt return resulting response.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
POST, PUT/UPDATE, GET, DELETE
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application programming interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
Service using axios: (or controller if a real simple getter)
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Modularity, simplicity, readability, and ease of modification and scale
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
Internal error on the server side. (this would be a non web dev related issue, this is back end)
```