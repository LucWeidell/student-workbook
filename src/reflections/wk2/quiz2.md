# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var let const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
Assuming this is about the literal definition of a function, it is a subprograms to accomplish a partictualar and hopefully singular purpose.(I.E. monster in the box to do a task)
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S:  Single Responsibility principle
O:  Open Closed principle
L:  Liskov Substitution principle
I:  Interface Segregation principle
D:  Dependency Inversion principle
```
**4.** Given this array:
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
```
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
index: 2:
Order in arrays: n-1 : reading left to right
  So if pineapple is 3rd its index is: 3-1 = 2
```
**5.** With these two objects:
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
IF/ELSE
Switch
Ternary
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i++ : increments i up one at the end of the iteration
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model
The HTML file/field is the core of the DOM.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
undefined, Boolean, Number, String, BigInt, Symbol, Object, Function, null
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
parameter is the banana word given during the function construction
argument is the actual value passed into the function during run time
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive is a value pre stored in the computer that the computer translates.
References are values new values made in the stack that are unique to that object or function.
```