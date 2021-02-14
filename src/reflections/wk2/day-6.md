# Week 2 Journal 6 

1. What is Scope ?

    Scope helps us determine the acessablity of our variables, the first type of scope is a local scope any variable that is declared within a local scope or a function can only be accessed within that scope. The other type of scope is a global scope when we declare a variable globally it means it was declared outside of a function and any function can acess that unlike a local scope.

2. What is Hoisting ?

    Hoisting is when Javascript decides to move declartions to the top of the script because of its default behavior. Your code doesn't really get changed around in the program that you're writing it in but when that code gets proccesed the declarations will be moved to the top and proccesed. Although hoisting exists for our benefit it is still best practice to just declare variables at the top of our code to reduce changes of bugs. 

3. In what cases might you use let vs const vs var?

    Let is what I will use in most cases with my coding process because of its improvement over variable. Let allows us to update the variable within its scope but it will not allow us to redeclare that variable within its scope. This makes it easier because our code will not be constantly getting redeclared within our Javascript making it easier for us to use the same variable over again. Unless its absolutely necassary I won't be using var in my code to save stress down the line. Const on the other hand is different from those two entirely, it cannot be redeclared or updated which makes sense since const is short for Constant. This allows us to have a constant variable within our script that is not allowed to change. It's usefull when we specifically dont want that variable to change in any instance. 

    https://github.com/dallenpyrah/js-challenges