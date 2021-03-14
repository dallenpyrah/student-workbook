# Week 6 Journal 4

- What is a nested route?

A nested route allows components to be nested inside of each other. We can route different components onto the same page or route components within components. This allows us to build more dynamic applications and multi page looking applications using a our single page. 

- When might you use a nested route? (other than the provided example)

I would use a nested route for something like our blog page. I have my home page and then when you click on a blog it takes you to the blog details page. On this page I have a blog post but I also have a nested component called comments on each blog post that I routed to it. 

- Can you pass parameters through nested routes? When might you use them?

Yes you can pass parameters through nested routes. We can pass the id from our parent element to our child element and now that component can have access to its parent ID. I used them on my comments with my blog posts because I needed them to know which blog post they belonged too and this was the best way. 

https://github.com/NikolaCop/pokevue