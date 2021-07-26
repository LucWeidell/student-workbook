# INTRO TO ASYNCHRONOUS CODE (Day 1/4)

## What are some of the signs and causes of Callback Hell?
1 A pyramid of Brackets and Parenthesis at the end of function
2 When line 1 finishes the entire function finishes
3 Calling itself repeatedly with lambda functions

## What does the asynchronous mean and how are callbacks involved?
Asynchronous means a functions that waits for it to be completed
Callbacks mean that call upon this next function once the asynchronous code is complete.

## Summarize the 3 ways to avoid / fix Callback Hell
1 Keep your code shallow: name and define functions
2 Modularize: use function hoisting and single purpose principles
3 Handle every single error: catch errors and report informative status

## Afternoon Challenge:
https://github.com/LucWeidell/trivia-site