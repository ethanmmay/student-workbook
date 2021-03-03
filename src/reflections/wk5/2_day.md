## Day 2

### MongoDB, Node.js & Postman

With the problem of our servers still being hosted locally, we introduced ourselves to MongoDB and created a cluster to store and manipulate the test data of gregslist. We built out our Cars functionality once again but this time, using our own server and API, whereas our old gregslist applications used the instructor's APIs and servers. We continued to use Node and Postman to connect to our database, and therefore learned a little bit more about the node server pattern.

1. One-to-One, One-to-Many, Many-to-Many.

2. Through the use of relationship objects we can create links in data that represent data relationships. We do this instead of embedding relationships because it creates one object that defines the relationship, where embedding would re-create or copy that data to each object that uses it. This uses more data in the long run and makes it much more difficult to edit all occurances of that data because it is not linked through a relationship object.

3. Using relationship objects, we can link many-to-many data to simplify finding the relationships between both types of data. However, naming conventions and multiple Id's can create challenges that make it easy to become confused. This is why it's important to plan out how you want your data to reference it's relationships beforehand, so you know what it should look like, instead of what it currently looks like.

Link to Project: https://github.com/ethanmmay/gregslist-mk3/