# Understanding Persistent Relational Data

**1.** When using the Vue `cli` what is the command to initialize a project?
<!-- enter you answer in the space below -->
```
vue create projectName
```
**2.** Where can you find the scripts to startup you project on localhost?
<!-- enter you answer in the space below -->
```
We can check Vues website for their commands or the way to startup a project on localhost is by running npm run serve
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for="" will loop through and display each item in our collection on our screen.
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
<template> <script> <style>
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov Substitution Principle
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
App.vue is where the vue router mounts our pages onto. 
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
The AppState is where all of our information for our application is stored, where the state in a component only stores information for that component. 
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
The responsibility of services in our vue projects is that they handle communicating with our server. We put all of our GET,POST,PUT, and DELETE functions here.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
The public file
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
<style> && scoped
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
Computed(() => AppState.comments) Computed allows us to watch data in our application, and change it on our screen when it changes in our application. 
```