# Week 5 Journal 4

- What is a virtual property?

A virtual property first off is additional fields for a given model. They are additonal model functions that can return values based on defualt schema values. This is helpful when we want to set or get two that have relation to each other. 

- When might you use a virtual property?

In the example given in the reading we use a virtual property to conjoin the first and last name of someone together. Even though these names are two seperate values within our schema we are able to use a virtual get method in order to display these two together. 

- How do you search by a virtual properties value?

We can use the get method to search for a virtual properties value. The way that we do this is by creating a get function through a virtual, that passes through this.firstname and this.lastname. Then we are able to access those properties on our vitrual. 