# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
One way or Two way binding. {{}} or : in front of an attribute + v-model
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Single Page Applications allow utilizing multiple components and a router to load only relevant information to the page.
This free up resources so that there isn't non-rendered components waiting. Also allows easy storage of variable in one state.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
On mounted runs the methods within the parameters before the component is loaded to the page.
This allows the developer to populate the date that will be needed to render the page.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
V-model two way data binds to the script for reactive rendering.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
<!-- @click, @submit... @ on directives are event catchers that are reactive vue directives. -->
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if, v-show, v-hide, v-else: allows the user to conditionally render things to the page with a reactive water on a data in the script.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The key attribute allows the iteration over data in a v-for which allows easy passing of props with a unique identifier
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
Slots give a placement identifier for placing a component or any template code within. Similar to a span html inject in base javascript
```