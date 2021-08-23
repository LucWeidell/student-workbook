# Capstone #3 (Day 4/8)

## What are the three main types of testing we can accomplish in Vue? What does each method provide?
Unit Testing:
Unit testing is make tests for whenever modular/ components are created in development.
These are create for edge-case testing and computation testing.
The big thing is these test remains helping to be confident that the feature is still functioning 100% as intended if
all test past
Component Testing:
Similar tests of assertion: these are tests that when a component is brought up: they are being loaded correctly:
the right data is stored: the right components are rendered.
These are great as they are compatible with vue.
These provide accurate error logs again with the response and expected value

End-To-End (E2E) Testing:
This is similar to the Postman requests where the server endpoint is verified.
This is incredibly important to make sure that data is being stored and read properly and that fields are never missing or in
strange states.


## What testing method do you think is the most useful? Why?
For our purposes End-to-End is critical as our Capstone is client->db->yelpApi which can lead to many
strange states, so the backend needs to be solid.
BUT GENERALLY:
While we aren't doing it as much: Unit testing is the best. Whenever writing code ALL edge cases
should be covered so if any functionality is broken it is fixed immediately before being sent to production is possible.

## What testing method do you think is the least useful? Why?
Least useful would probably be component Testing: Vue has a lot of built in error detecting for component mounting
failures. Also with the vue-devTools A lot of the information gained from component testing is viewable.
If this is full stack: security/efficiency/stability of the server and the edge testing for units triumphs.