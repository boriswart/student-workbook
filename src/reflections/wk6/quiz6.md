# Understanding Persistent Relational Data

**1.** When using the Vue `cli` what is the command to initialize a project?
<!-- enter you answer in the space below -->
```

Syntax: vue init <template-name> <project-name> example: vue init webpack-simple …

```
**2.** Where can you find the scripts to startup you project on localhost?
<!-- enter you answer in the space below -->
```
npm install -g vue-cli. This command will install vue-cli globally. 

```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
cd new-project. Change directory to your project folder.
npm install. Install all the dependencies required by the template as listed in …
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
<template></templte>     <script></script>  <style></style>
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov substitution principle  
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
<template></template>
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
AppState contains the state of current memory elements in your application The state object is setup to be a local reactive version of needed current memory that can have a binding with elements in your template view.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
To change memory elements and to setup business decisions as to how that memory is changed and by whom. Also to set up communications to API - backend elements.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
main.js  
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
style scoped
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
reactive or watcheffect E.G 

    watchEffect(() => {
      carsService.getCarById(route.params.id)
    })

but also computed .

```