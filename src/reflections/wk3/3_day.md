## Day 3

## More MVC - Forms and Templates

Starting the day off with a simple palindrome checker function, we dived into Forms and Templates in MVC architecture. We then moved onto building a CraigsList type application using MVCS architecture that utilizes more Templates and Format than our Vendr application. After lecture I finished both GregsList and Vendr, and felt much more confident with MVCS architecture than I did before the day. Not only do I see the usefulness of it's security purposes, I see how it can help organize code and specialize each file for a more nuanced task.

#### 1. What are the two common operations that we will set in the handler?

```We will preventDefault() in our JS to prevent the form from linking to a new page with our data in the url. We also create a button with an onsubmit property that calls our Controller to perform the function using the event. This allows us to set the form data to our constructed variable, allowing user-inputted data to exist in our JS.```

#### 2. What do you have to make sure you are doing with every Get to insure the value does not become undefined?

```If the question is asking about importing, we must remember the .js file type to prevent the wrong route from being accessed. If the question is asking about get functions in the Model, we must return a value to prevent it from being undefined.```

#### 3. What are some of the benefits of the proxy object that we are using in our structure for applications?

```It hides the data manipulation from the user's view by only making changes in the service file.```

Link to Project: https://ethanmmay.github.io/gregslist