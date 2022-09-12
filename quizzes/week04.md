# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
synchronous code happens right away or code that happens in a specific order
asynchronous there is a "wait" in which the execution of a task is not guaranteed to occur in a specific order
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
Procedure or function in a program that wait for an "event" to occur. like a mouse click, key press or internal timer.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open/Closed, classes should be open for extension but closed for modification.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A Call back function is a function passed into another function as an argument, which is then invoked inside the out function to complete some sort of action.
A higher order function is any function that takes in another function or returns one out.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A Promise is asynchronous which means it takes time to resolve or finish, a returned object to which you attach callbacks instead of passing callbacks into a function.
using the |.catch()| method will capture an error from a promise and accomplish new actions after the promise is rejected.

```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
GET, the most common
POST, common method to modify a resource.
PUT, method to request ser-side to generate entirely new resource or update an existing one.
HEAD, method to extract information from a particular resource.
DELETE, method used to entirely remove a resource from a location specified in the URL.
PATCH, series of instructions that implement partial changes to the targeted resource.
OPTIONS, evaluating the various options of a particular resource.
CONNECT, build a connection to a server by the client-side
TRACE. reflects the content of an HTTP request back to the client.
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application
Programming
Interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```

```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Essentially adding layers of firewalls to data and information in your program/application.
combining elements to create proxy entity for the purpose of hiding and protection information. 
all the object's data is contained and hidden in the object and access to it is restricted to members of that class only.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
HTTP response code with a successful request is  a "200 OK" 
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
The 500-error status code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request.
```