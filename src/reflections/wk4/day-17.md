# Week 4 Journal 3

1. What is the purpose of Async/Await?

When we put await in our code before the api request, we are not going to run the rest of lines after that until we get a response from the api. The reason why async is involved is because we can't declare a function with await without putting async in front of it. Aysnc states that we are going to get a promise back whether or not that is goinging to get resolved or not is up to the data we get back from the server.  

2. What must you do in order to await a promise inside of a function?

The way that we have been doing this in class is by putting await in front of our api request, for example we are going to declare a variable of res, which is result equal to await and whatever api request we are using. const res = await api.get('').
This will await a promise inside a function in order to get the response back before we run anything else. 

3. What are some of the primary benefits of Async/Await?

Some primary benefits of using async and await is that our code is much easier to read. Relating back to callback hell when we use this patter our code is a lot more organized and we will have an easier time coding our applications. The next benefit is await/async functions can be chained very easily, making it easier on us to code our applications. The last benefit is for debugging promises, when we use async/await it makes debugging easier because the code runs synchronously resulting in hitting the debugger in the order we want. 

https://github.com/dallenpyrah/pokemongame