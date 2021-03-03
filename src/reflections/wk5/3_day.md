## Day 3

### Learning Data Relationships

After an interesting morning challenge testing our abilities to use multiple data types, we started reviewing what we learned for the past couple of days and started learning about data relationships and how they can be used to explain multitudes of ideas in both our physical world, and our programming world.

1. A document in Mongoose is a collection of data. It's a response with information created, passed into or deleted by the program. Therefore a subdocument is a smaller piece of data that is usually pulled into a reference object. 

2. We use the populate function to retrieve data from another service as a subdocument, and append it onto our relationship object.

3. Since subdocuments are retrieved data, we must modify the data at it's origin to add to the data. When we do use populate to retrieve our subdocument, we can use extra parameters to specify what exactly we want to keep when we populate it. We can do this through specifying what we want to populate, or one thing we choose not to populate.

Link to Project: https://github.com/ethanmmay/classroom/