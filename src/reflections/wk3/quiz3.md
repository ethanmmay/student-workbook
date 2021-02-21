# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
  Abstraction, Encapsulation, Inheritance and Polymorphism
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
  staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
  Grouping functions/code into classes or just generally grouping code into smaller parts for future use of a smaller part or simplification. 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
  Single Responsibility. It means that a function or class has one responsibility and does not provide the entire project's functionality.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
  A class often has a constructor function and definitions for how an instance of it might be built. For example a class can construct an object, and that object is the instance of that class.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
  Proxies are objects that act as a middleman between the user and the service (data manipulation location). They hold a fluid form of the data available for import throughout the app.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
  To designate areas for where data manipulation, call-passing and model-defining is done. Allows us to use a ProxyState which both hides data from the average user, and maintains a fluid area where it can be called and changed. We can also use the observer pattern to monitor the data, and update the page when it has changed.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
  To pass calls to the service from the user's input or interactions with the page.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
  To manipulate data and use functions to make changes on the page.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
  To define the types of data that will be changing in order to edit the page.
```

