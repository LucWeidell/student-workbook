# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
This is what npm loads to bring all of our modules. These can include: axios, boostrap, fontAwesome.
```
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
Need it at the highest level within the server and client. Since the client and server need different modules: tipicall there is one for each.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm build for herokuapp: npm serve for client and server deployment
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
Environmental variables/setting found in the env.
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
From the website and from the running and bootup of the app when opening the url.
Typically the herokuapp terminal is better to check for failures.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Push to production: or whatever directory it is pointing at.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
So that production/stable code is maintained while development can continue.
Even more branches can help with modularity of work.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Every Sprint Review/Code Review.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merging.
```
