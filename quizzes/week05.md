# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
Create
Read
Update
Delete
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
Create -POST method
Read -GET method
Update -PUT method
Delete -DELETE method

```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
Object Relational Model, represents the website's data as JS objects, which are then mapped to underlying database.

SQL the database's native query language
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
PUT AND DELETE
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
Asynchronous
Synchronous
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import {Schema} from "./Model.js"
let Schema = NEW.schema
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
software that enables one or more kinds of communication or connectivity between two or more applications.
  making it easier to connect applications that weren't designed to connect with one another.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```

```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
https://randomImageSite.com/api/search?tag=winter
```