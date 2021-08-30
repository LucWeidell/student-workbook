# Working in a Professional Environment

**1.** What is Inheritance?
<!-- enter you answer in the space below -->
```
Inheritance is where a child of the parent class inherits the variables and methods of the parent.
In Js this is the extends property in the constructor.
```
**2.** What is the `Singleton` design pattern?
<!-- enter you answer in the space below -->
```
The Singleton Design patter is what we use around the appstate of the client. Where a proxy was created that buffers the real appstate
from the user. This means only on 'single' instance the targeted object is created maintaining better security.
```
**3.** What is the `Observer` design pattern?
<!-- enter you answer in the space below -->
```
The observer design patter focusses around catching a certain event and then triggering certain code.
Before this was:
1. Catching events on forms
2. Proxy State.On
3. Computed/Reactive
4. WatchEffects
```
**4.** What is the `Strategy` design pattern?
<!-- enter you answer in the space below -->
```
Strategies are a design idea that we dont know exactly what the run time data will appear like so we cant predetermine a path.
Receive the information first and then do something. A good example could be we dont know how many players in connect4 may play:
So make a strategy that will get that info first and then do something with it.
```
**5.** What is the `Factory` design pattern?
<!-- enter you answer in the space below -->
```
The factory design hasnt been used largely by us yet, but the idea is to encapsulate the concrete classes and models into another interface/class where common names are used to do a variety of functions under the hood. So every child class below may have a
'create' function that the factory can call without having to know exactly which specific class to call.
Best example so far:
1. MongoDb .create
```
**6.** What is test driven development?
<!-- enter you answer in the space below -->
```
Test driven development is a pattern of development where the unit/ edge case tests are written before any functional code.
This helps to structure out each function/class as well as the parameters and returns that will occur.
This leads to more stable code but usually longer development/design times.
```
**7.** In Scrum/Agile what is the DoD?
<!-- enter you answer in the space below -->
```
Definition of Done: what is the standard to check off something in the the backlog as finished.
```
**8.** Give two examples of a user story:
<!-- enter you answer in the space below -->
```
1. When a user click the login button: they are prompted with a login screen asking to signin or signup with {}
following fields. When the click the final signin the prompt is closed and the status of their account is updated.
2. When a non-logged in user clicks the random button they are presented the with a random restaurant with all the details, but
will not see any buttons to save if they have been or are going to that restaurant
```
**9.** During which ceremony is your Sprint Backlog created?
<!-- enter you answer in the space below -->
```
At the beginning of the project. Before Sprint Planning the first time.
This is reviewed after each sprint though to be updated accordingly.
```
**10.** In which of these ceremonies are Tasks assigned to you?
<!-- enter you answer in the space below -->
```
Sprint Planning
```