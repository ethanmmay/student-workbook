## Day 4

### Implementing Auth0

Starting the day with a simple function that checks if three given values can be the lengths of a triangle, we studied the Auth0 API and learned how to implement it's architecture into ours, providing simple and easy to use security for our new many-to-many capable databases. With Google and Auth0's partnership, it was a little confusing to set up and while it introduced many new Id's to keep track of, I believe I have a decent understanding of how we can use AuthO to process users and their qualifications for certain HTTP methods.

1. A virtual property is a property on a base object that is open for changes. 

2. You can use a virtual property to create a derived object from a base object. We have virtual properties on our APIs that define the version of an object and many other behind the scenes metadata and identifiers.

3. You can create a non-virtual property that reads the value of a virtual property in your model, which can then be used in a query paramter that defines what data you retrieve based on virtual property values.

Link to Project: https://github.com/ethanmmay/auth0/