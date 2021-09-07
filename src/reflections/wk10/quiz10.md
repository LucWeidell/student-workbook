# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Determines the accessibility to other files in the project. Helps further encapsulation.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Class contains methods, and provacy layers as well as properties. Structs are a definition type for formatting data but do not contain everything available to a class.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
New
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
Public. Any file that can import this class and makes an instance/ child of of Car can run this.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
The return type of the method.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
You cannot create a car directly it must be inherited.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Allows a inherited class to overload/modify a parents function.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, protected, private, abstract
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
That file where the class or method was written.
```