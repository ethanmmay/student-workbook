# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
    Scripts, Template Documentation or General Information about the project/workspace.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
    Top-level. Above the client and server folders. Because it must have access to both folders to run their deployment scripts.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
    npm run build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
    AuthConfig.js and .env files are used to provide variables for how to host, connect and where to read/write database data.
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
    Via Heroku's CLI you can use "heroku logs" to display them or see them built on-site at "dashboard.heroku.com"
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
    Re-initialize your GitHub repository in Heroku
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
    Branching is a large part of version control because if you want to take different directions with apps or want to view old versions in case of reversion, you must have a branch to return to or create.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
    Code review should happen after automated tests run successfully for the first time.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
    Merge
```
