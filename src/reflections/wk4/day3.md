# WORKING WITH MULTIPLE API'S (Day 3/4)

## What is the purpose of Async/Await?
Syntax built on the use case of promises.
The calling code will not paused until the promise is resolved successfully or maybe not called at all if rejected promise and error is caught.

## What must you do in order to await a promise inside of a function?
Function must be async: "async function ....."

## What are some of the primary benefits of Async/Await?
Async helps readability: (states either internally or explicitly promise will be returned)
  2 Chaining is simpler to read and with await allows stoppage of callbacks without timers
  3 Simple to call asyncs repeatably or awaits repeatedly with little code.

## Afternoon Challenge:
https://github.com/LucWeidell/pokedex