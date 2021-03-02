# Week 5 Journal 2

- What are the three types of relationships?

A one to one relationship, which describes a relationship between two entities. A one to many relationship, which is when one side has a single relationship but the reverse side can have many. Finally, a many to many relationship where they both might have many relationships to each other. 

- What are the benefits of the traditional linking of relationships instead of Embedding

Linking a relationship instead of embedding a relationship can have many benefits first off, when we link comments to a blog post the file size will be less likely to hit the max size we are allowed. It is also much easier to retrieve comments when we want them on our blog post but the downside is we have to make requests/read for each one if we have a lot of them it might slow it down. 

- What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?

When we are deciding on how to manage a many-to-many relationship we have to look at our problem and decide which solution is going to work best for us. We have three different ways of embedding, one way embedding, two way embedding, and three way embedding. We have to decide which one of these is going to make our application run the smoothest, if we have a catalog of books that are ever changing but categories that stay the same we may want to embed the category (one way) into each book so we dont have to change the categories everytime. 