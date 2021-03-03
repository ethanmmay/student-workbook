## Day 1

### Introduction to Node.js

Using the bcw-create tool, we studied the innerworkings of the templates and how the server passes our controller and service data through to a database. Using new formats for the observer pattern, for controller try/catches, and even a new API link format, we gathered a rough understanding of what it takes for a Node.js server to tick. We also used an app called Postman to send http requests to our server to test our observers and our functions for retreiving, creating, deleting and editing data.

1. A query string helps narrow down the data received by an API and evaluate conditions that sort said data. It is the combination of many different query parameters.

2. A query parameter is what evaluates what a key can be equal to, which then tells the request to only display the data where the query parameters are true. It's format is "[link]?[key]=[value]" It starts with ? and that is also what you can use to distinguish between the previous parameter, and the next.

3. If you have a large data set or you want to make sure your get request works with query parameters, it is useful to use them to narrow data or just test them to see if they work with your API.

Link to Project: https://github.com/ethanmmay/node-intro/