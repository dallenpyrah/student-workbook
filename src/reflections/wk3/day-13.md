# Week 3 Journal 3

1. What are the two common operations that we will set in the handler?

Some common operations we will set in the handler are, setting the object, property and value in the parameters of the function on set. That way if we want to later down the line we can add items to our object, and the set function will set it so that it is now on the object. 

2. What do you have to make sure you are doing with every Get to insure the value does not become undefined?

If we try to console log the object thats stored in our Get we will get whatever we decided to put in the console log but we will get undefined for the object value because we reset that to whatever is in the console log. In order to combat this we can pass through the obj and prop and parameters and still console log what we want to but we have to make sure we return the obj[prop] so that the value doesn't come back as undefined. 

3. What are some of the benefits of the proxy object that we are using in our structure for applications?

The benefits of using a proxy and vast, in the example in the reading they wanted to use a proxy to make the id property private. In order to do this we needed to make a proxy so that if someone tried accesing that id property and it wasn't us, we create a if statement and it will throw an error at the user saying they cannot access that property. It helps us keep things private, while still being able to access it ourselves. 

https://github.com/dallenpyrah/latewinter2021-gregslist