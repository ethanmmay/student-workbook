# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
    Synchronous code moves to the next process as soon as it's finished with the last, meaning it has no reason to wait to execute code, and therefore just does it. Asynchronous code uses network requests to other programs to retrieve special data it needs for the following processes. Therefore it must wait, and therefore works asynchronously to a connected network program.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
    An event listener records the data emitted from an "event" on the page. Usually a form, the event listener records that data and stores it within the event variable for future use by a program.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
    The O stands for the Open-closed principle. This principle states that developed programs should be open for expansion, but closed for modification. When a program works and no further features are desired, the program or module should now only be edited for extended functionality.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
    A higher order function uses a smaller, usually modular function to return a modified datum to the higher-order function. Sometimes higher order functions can define an entire process through smaller modular functions.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
    A promise is a status a network sends to the program requesting data. It has three states. Fulfilled, Rejected and Pending. You can capture an error from a promise if the promise is Rejected and you save the promise to a variable which is then logged into a console.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
    GET, POST, PUT
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
    Application Programming Interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
    The Service is responsibile for using Axios to make requests over HTTP to a API.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
    Encapsulation is what enables programs, functions and classes to be modular. It is the idea of creating code with basic functions and using them in multiple places, creating less code overall and more tools for future projects. 
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
    Codes 200-299 are for successful or fulfilled requests.
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
    It is a server error letting the requestor know that something has gone wrong server-side but it could not be more specific.
```