# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Classes and instances
Inheritance
Encapsulation
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
let property = staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Objects provide an interface to other code that wants to use them but maintain their own internal state. the internal state is kept private meaning can only be accessed by the object's own methods.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
a Class is a blueprint which you use to make an object aka the idea of what a home is

and an instance of class is an concrete object or a real home which is an item and a case of instance of a class.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
allows creation of an object that can be used in place of the original.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The design is used to distinguish the presentation of data from the data accepted from the user to the data shown.
Helps the reusing of code and parallel development which makes using it much simpler and easier to use.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
Does most of the work, provides the support for input and converts the input to commands for the application. does most of the displaying of data and taking in data from user.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Helps the user to see the model's data.
Main job to access the model's data, a visualization of the information that the application contains.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
Primary part that contains the applications information purely, independent of the user interface, controls the logic and rules of application.
```
