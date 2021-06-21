# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
':' character infront of a key such as :key or :src will bind a data element with a reactive variable ... V-bind also does the same as a long hand methos.  In addition the class bind can bind an element to change a style for color or display determination 
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Sinle Page Application.   Vue allows you to create a single page application by determining the portion of your page that gets rendered dynamicly.
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Faster ... can reload portions of your page very quikly and give a more dynamic feel.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
Means that when the postion of you code is Mounted the hook is selected so that you can launch the things that need to be daone at that time. A dynamic hook.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
The v-model Vue directive allows us to create a two-way binding.

You can bind a form input element for example, and make it change the Vue data property when the user changes the content of the field:
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
It is a listener that is activated on a data element to sense a change. Such as a button push for example.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if,  v-else, v-else-if
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
it sets up the index of the for loop.  Best if unique.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
It is a depricated distribution outlet to navigate to a certain area.
now: 

<navigation-link url="/profile">
  Your Profile
</navigation-link>
```