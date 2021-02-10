# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
  var, let and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
  A customizable section of code that can be called with arguments to tranform data or manipulate the webpage
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
  Single-responsibility principle, Open-closed principle, Liskov substitution principle, Interface segregation principle, Dependency inversion principle.
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
  2. Arrays start at 0 and each comma seperates an element of the array, giving it it's own index
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
  if(expression)/else, or switch(expression)
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
  "Statement 3" also known as the incrementer is the area of the for loop that is executed after each loop to continue the loop, and hopefully reach an endpoint at some point. Without it, the for loop would loop endlessly. Put i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
  Document Object Model. The HTML file
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
  Primitive Data Types: undefined, Boolean, Number, String, BigInt, Symbol. Structural Types: Object, Function.  Structural Root Primitive: null
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
  A paramater defines what the argument will be when it is passed into the function. The argument is what data is passed through to the function.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
  Primitive values store the actual data of a variable. Reference values store the address for the data of a variable.
```