# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
The difference is that our programs don't have to wait for the asynchronous code to run, it will move onto the next line while synchronous code runs line for line it won't move on till the previous one is ran. 

```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
A procedure in javascript that awaits for an event to occur, for example proxystate.on("cars", _draw) this listens to the first event "Cars" and any changes to that will trigger our draw function. 
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open-Closed principle, which means objects should be open for extension but closed for modification. 
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A callback function is a function that is passed to another function with the expectation that the other function will call it.

```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
When we request information from a server it gives us back a promisse, there will be different results with that promise if any part of our function fails it will result in that promise not being fufilled and we can console log that error. 

```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
Get to get information, Post to post information, Put to replace information, and Delete to delete information. 
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface

```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
Our service controller

```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
To keep the information that we don't want anyone else seeing enclosed and only showing the information that is required. 

```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```

The response code is 200

```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
Internal Server Error 
```