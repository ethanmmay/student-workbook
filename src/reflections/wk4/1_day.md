## Day 1

### Introduction to APIs and Axios

With a difficult week over, we were set up to move into the backend and learn how to receive promises and data from an API. After messing with a star wars wiki database and a trivia database, I feel much more confident in the ease of api requests.

1. Using axios we often times have to use .then and .catch to prevent errors from going uncaught and defining what we want our program to do after or if we retreive data. However we also tend to nest these, which can create an extremely annoying and confusing environment making the scope and uses of the variables practically unreadable. This is callback hell.

2. Asynchronous means that the code cannot run while grabbing data from an API. Therefore it must wait until it has received the data, or expire the request with a timeout. Callbacks are the outcomes of promises that are made to ensure data's delivery.

3. Use await. Limit your then/catch usage. Use larger api requests.

Link to Project: https://github.com/ethanmmay/open-trivia-api/