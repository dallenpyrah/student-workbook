# Week 4 Journal 1

1. What are some of the signs and causes of Callback Hell?

One of the signs of Callback hell is when there are a bunch of }) these at the end of our functions. This happens when people try to write javascript where execution happens visually top to bottom. Overall its just caused by poor coding practices/habits which can be fixed. 

2. What does the asynchronous mean and how are callbacks involved?

Asynchronous just means it will take some time or it will happen in the future. We use callbacks when we are talking with servers or API's which is not our data, so maybe downloading a file from a website and displaying it on ours. This will take some time in order for it to load since we have to call that into our program. This means that our code wont run synchronously, Javascript makes sure our program still runs and keeps that function in storage until it getse the data it needs while it runs the rest of our program. 

3. Summarize the 3 ways to avoid / fix Callback Hell

The first way is too keep the code shallow this means naming functions so that they arent anonymous which makes it easier for us to read the code and understand what it is doing. This allows us to move functions around making the code look cleaner and be able to reference them by their names. The second way to avoid Callback Hell is by creating modules, these seperate parts of our code into bite size chunks rather than having it all in one place making it hard to read and understand. This way each module has a specific task to do, you wouldn't want to go to work and everything is unorganized while no one has been told what their specific task is. The third way is to handle every single error! No matter what error it is we should make sure that we take care of it because even if we dont think it has anything to do with our application or its not affecting it, we should still try to resolve it so that our applications have less of a chance at failing. 

