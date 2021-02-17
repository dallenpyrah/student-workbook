# Week 3 Journal 2

1. What is the purpose of Encapsulation?

The purpose of Encapsulation is to hide things from the people using our applications. For example in our Moon Miner games anyone could go in and adjust the cheese count because there was only one Javascript file and nothing was hidden so any of those lines of code we wrote could be modified. With Encapsulation this stops that from happening because we have different sources that have different purposes. All of our crucial data we don't want them to see will now go in files that will send information directly to the controller that just draws on the function. 

2. What were some of the problems with closures and the underscore prefix?

Before E6 came around there was really no way to denote whether a class was private or public to combat this developers started to use underscores to denote whether or not something was private. It can lead to detials in our code being leaked because of its easy accessabilty, and at the same time its also easier for hackers to get into our programs and break our software. 

3. How do we create private variables in a ES6 Class? Why would you do this?

const myCounter = new Counter we would have all our data underneath this stating what this variable or function can do and then we can export that out to another file so when someone tries to go in and look at our code they can only see the function being called they can never see what that function acctually entails. A lot of companys like Facebook and Instagram do this because they dont want people seeing their algorithms that control the way people see peoples posts on their app, in fear that other companies might try to steal their data. 



https://github.com/dallenpyrah/vending-machine