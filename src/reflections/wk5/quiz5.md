# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
    Create, read, update and delete
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
    C - post, R - get, U - put, D - delete
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
    Object-relational Mapping. Mongoose was created to optimize the process of validation, casting and ORM. We use mongoose.
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
    POST and PUT both use a body to specifiy what data to create or edit.
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
    Asynchronous, Synchronous.
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
    Value, ../Models/Value.js, mongoose
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
    Middleware makes the programming world run. Mongoose, node_modules and countless other tools are all middleware that help programs achieve menial tasks quickly through encapsulation and modularism. Middleware makes the profession of programming much more accessible even though it expands upon the tools programmers use. It minimizes the information you need to know to allow you to have a easier time building, learning and testing applications.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
    Request, response
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
    http://placeholderlink.com/api/data?tag=winter
```