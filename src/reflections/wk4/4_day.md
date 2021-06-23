## Day 4

### Audio & Video Data + Review

Starting the day off with a simple minutes to hours conversion problem, we reviewed the basic parts of using MVC architecture to access an API and retreive data. Reviewing the small parts of the code really helped solidify the knowledge of what each part of the MVC pattern does. After lecture, my partner Daniel and I started working on building a search tool for the iTunes API.

### 1. What does REST stand for, and in simple terms what does it mean?

```Representatial state transfer is the standard for API configurations. It's what allowes Axios to be able to reach multiple different APIs regardless of their data organization, hosting site or methods. The HTTP methods GET, POST, PUT and DELETE are all methods of a RESTful API.```

### 2. What does Stateless mean?

```A stateless program is a service that is not dependent on it's previous state. It's data and methods of holding, editing, and transferring data are all dependent upon user input, and not a previous state.```

### 3. What URL pattern is used when writing a RESTful API?

```URLS in RESTful are based on the type of resource being accessed. The intent is to proceed through arrays of "collection" resources to retrieve data that is eventually going to be used as a "singleton" resource which is a standalone piece of data. We use axios to retrieve collections from APIs. We then use the singleton data in those collections as a display on the page, or value for running a program.```

Link to Project: https://github.com/danielfasula/music