# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
Let
Var
Const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A block of code designed to perform a particular task.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S - Single Responsibility Principle (known as SRP)
O - Open/Closed Principle
L - Liskov’s Substitution Principle
I - Interface Segregation Principle
D - Dependency Inversion Principle

```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Pineapple is position (2) because all arrays begin with  0  Ie..(0,1,2,3,4)
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
if(array.length >=4){
  return(stop function)
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
Operator & expressions  incrementor ++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model,
the data representation of the object that comprise the contents of a document on the web.
the index.HTML file.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Primitive values (immutable datum represented directly at the lowest level of the language)
Boolean type
Null type
Undefined type
Number type
BigInt type
String type
Symbol type
Objects (collections of properties)
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameter: is the variable in the declaration of the function
Argument: the actual value of this variable  that gets passed when the function is called.
used sometimes interchangeably

```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
primitive values are strings,numbers,booleans,null,undefined and symbols

 while reference values are objects {}, array, map. 
 Reference value stored in the variable location (objects or arrays etc..) and is a pointer to a location in memeory where the object is stored.
```