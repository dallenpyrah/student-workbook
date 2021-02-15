# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, const, and var
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a subprogram designed to perform a particular task. 
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility, Open / Closed, Liskov Substitution, Interface Segregation, Dependency Inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
2 because the index starts at 0 it would be 3 spots from the left since that is where the computer starts to read from. 
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
An if statement is a conditional statement, and an example would be if(i = 0; i <= 10; i++){
  console.log(i)
}else{
  console.log('nothing')
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model, the first file we access is the id that is in our HTML file. 
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
undefined, boolean, number, string, bigint, symbol, object, function, and null
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is what we pass through the function when we first write it so like function getDogs(dogs, cats){"dogs and catswould be the parameters"} when we call the function later on we would pass through our argument function getDogs(1,2){'1 and 2 are our arguments here'}
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive variable store the actual value, and reference variables store the addresses of the the objects they refer to.
```