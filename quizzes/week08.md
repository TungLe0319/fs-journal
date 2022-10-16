# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
holds various metadata relevant to the project
handles the projects dependencies
usually in the project root
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
the root because it's used to give npm that allows it to identify the project, take care of dependencies 
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm i
npm run build //pretty sure this one
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env file
env.js file
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
heroku dashboard
heroku logs
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Clone the repository from GitHub to your local device: git clone <YOUR HTTPS URL FROM GITHUB>
Make your changes, and commit them to GitHub
Login to your Heroku account
Set remote for your project
Push to Heroku master to deploy updates
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
allows teams and developers to collaborate and work together in one central codebase
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
before working branch is merged with the main branch
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merging
```