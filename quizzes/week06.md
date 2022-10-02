# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
index.html
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
Technically nothing. They use the same .vue model. pages are refrenced in routes and components are loaded when called
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
<template><script><style>
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
 Liskov substitution principle: 
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
app.vue
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
AppState hold data separate from the component. the objects in a component can grab that data and modify it without the AppState caring
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
For our projects so far Services mostly handles our GET/Post/Put/Delete requests
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
App.vie
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
<script> scoped
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
reactive
```