# INHERITANCE AND INTERFACES

## What does Inheritance accomplish for us in C#?
Inheritance gives child classes the properties of the parent and can also pass methods.
Great for code reduction.

## How does Member inheritance work in C#? Does a class inherit all members of the base class?
This is done with the : after the class name definition. The Member just inherits
values or methods from the parent not other siblings.

## How does accessibility affect inheritance?
If a parent is private all corresponding values for the child are private if parent is public
the child can still be private.