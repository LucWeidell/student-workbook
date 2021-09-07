# Introduction to C#

## What are the three categories of data types? How are they different?
Value type: Basic data value types as we know them: int, char ....
Reference type: A value type that contains a pointer. This needs to be shallow copied to be disconnected from other parts im the code.
Pointer type: A pointer looks at a particular value in memory. Changes here change all points in the code where this value is read from.

## What are the Value-type data types? What differences do you notice from JavaScript?
Types: bool, char, decimal, double, enum, float, int, long, struct, there are still more...
The difference from JS is these are defined on creation, also these are also stored in memory/ stack unlike in JS.

## In your own words how do Reference types get stored in memory? How does this differ from Value types?
Reference (contains Pointer): looks to Pointer: Pointer looks at memory in the heap: reference reads from that location to get value. If any values change in heap it will change every reference.

# Afternoon Challenge:
https://github.com/LucWeidell/rock-paper-c-sharp-console