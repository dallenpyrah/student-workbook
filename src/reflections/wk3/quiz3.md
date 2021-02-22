# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction, Encapsulation, Inheritance, and Polymorphism 
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
Property.staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
It is apart of the pillars of object oriented programming and it is meant to hide certian aspects of our application from the users. We can choose what to display and what not to display with encapsulation. 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility Principle
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
``` The difference between a class and an instance of a class is that class variables are shared between a class and all its subclasses, while class instance variables only belong to one specific class

```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
Its an object that wraps another object and intercepts the fundamental operations for that object. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The purpose of the MVC design pattern is to seperate things into three seperate interconnected elements, which at the same time helps us encapsulation data from the users. 
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller takes in all the data from the users and relays that information, there is no vital information available to the customer here. 
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service holds all of our business data for our application, hiding it from our users.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
This manages the data of the application and recieves input from the controller, this is where we will have our templates that will draw HTML to the main page dynamically. 
```

