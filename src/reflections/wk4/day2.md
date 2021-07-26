# HTTP REQUESTS CONTINUED (Day 2/4)

## What are the three states of a Promise?
Pending, Resolved or  Rejected: then return to Pending

## How do promises seek to resolve the issues of "callback hell"?
Promises guarantees the code that there will be a guaranteed response, pass or fail.
It also acts as the marker for when the code can continue versus writing a while statement or multiple timeouts.
Simply allows chaining

## What is the difference between .then() and .catch()?
Then: if promised resolved: code 200: do this
Catch: If not 200: Throw error and do this: but dont break application


## Afternoon Challenge:
https://github.com/LucWeidell/creglist-apis