## Day 4

### Complex Array Methods & MVC

Continuing our adaptation to MVC, we moved on to more complex websites and data manipulation. Starting with a morning group problem about changing orientatation and moving in a direction on a grid. Then during lecture, we built another program to practice MVC and Forms. However with this one we did some nested classes which helped further my understanding of the file structures and how they connect through imports/exports. After lecture we started on our Darryl's Storefront site where we must create a more complex Vendr application using MVC.

#### 1. What problems does the Observer Pattern seek to solve?

```The observer pattern solves the problem of putting your draw function in every function that changes page-drawn data. ```

#### 2. What are the three mechanisms of the observer pattern?

```The ProxyState.on function defines the observer function and lets the program know to watch the variables in ProxyState to preform a function. The first paramter of the ProxyState.on function is the variable to watch. The second parameter is what function to call when the observed variable changes. Usually this is your draw function.```

#### 3. Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

```By maintaining a fluid environment for variables, we can monitor them with ProxyState.on to "magically" update them.```

Link to Project: https://georgecondit.github.io/Dayrall-sUsedSportingGoods