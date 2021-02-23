# Week 4 Journal 2

1. What are the three states of a Promise?

The three states of a promise is pending, resolved and rejected. Just like in real life promises within javascript work the same way. 
When we request information from a server the promise is pending until we get the result back and it will either be resolved or rejected depending what that result was. 

2. How do promises seek to resolve the issues of "callback hell"?

By using promises with callbacks we are able to chain multiple callbacks one after another making the code look cleaner and, possibly run smoother this also fixes the readability of our code. Now our callbacks are in promises and if the condition is met the promise will be resolved otherwise it will be rejected.

3. What is the difference between .then() and .catch()?

.then() method is used for when a promise is resolved and it will move onto the next thing that needs to be evaluted in our code. This is different to the catch method, the catch method will only run if the promise failed or was never resolved. Then we can throw an error out to our console and we will be able to see that the promise failed. 


https://github.com/dallenpyrah/latewinter2021-gregslist
