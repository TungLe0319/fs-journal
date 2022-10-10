# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
 v-bind (Binds data one way)
 v-model ()

```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Speed,
It costs less,
Security,
code reusability,
more mobile app friendly
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
It has a set of methods nested in which will run once the application starts and Vue has finished running all of it's processes.
runs after the component is first rendered to the DOM.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
a directive that creates a two-way data binding between a value in our template and a value in our data properties,
a common use case for using v-model is when designing forms and inputs
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
@click
attach functions and listening to an element
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if
v-else-if
v-else
v-show
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
lets vue have direct reference to items in a list of items. allows for better rendering.
 to give vue a hint so that it can track each node's identity and thus reuse and reorder existing elements.
  good practice to include one.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
a tool for recreating reusable components in vue
A slot in an area in a component where you can pass HTML from a parent component
```