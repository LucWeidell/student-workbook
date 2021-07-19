# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
The 4 are: abstraction, encapsulation, inheritance, polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff.name.
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is the act of decoupling and grouping data structures in order to organize and obscure exposure of data from unneeded windows.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility: building code in which everything has a single purpose, makes readability much simpler.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
Instance of a class is a class that has been defined, identifiable because it will have a variable name assignment to it. A default class is just a high level abstraction of data with not way to access the abstracts data.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is an object that is wrapped around an actual object. This allows for manipulations of the proxy without effecting the original.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
Purpose of MVC is to encapsulate and organize code such that the view, controller and model and are differentiated for ease of readability and functionality.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller draws to the screen and passes all other functionality jobs to the service.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service does all manipulations of the Proxy as well as all general functionality needed in the code.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is the definitions of the data structures used throughout the program. This includes all data classes to which the state will refer to and centralizes what properties the services can pull.
```

