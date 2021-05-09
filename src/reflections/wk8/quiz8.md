# Deploying Applications

**1.** What is the package.json file used for?

<!-- enter you answer in the space below -->

```
It stores all required dependency references that your app will require to function.
```

**2.** At what level of your project do you need package.json when deploying your application? Why?

<!-- enter you answer in the space below -->

```
At the very beginning, when ensuring that your project has actually *installed* all required dependencies.
```

**3.** What command will ensure that your Vue code is compiled properly for deployment?

<!-- enter you answer in the space below -->

```
"npm i" will install all dependencies referenced in your package.json
```

**4.** **\_\_\_** are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.

<!-- enter you answer in the space below -->

```
.env files, both Client- and Server-Side
```

**5.** What are the two ways to view the logs from your Heroku app.

<!-- enter you answer in the space below -->

```
When accessing your app, the logs are visible from the home page.
They are also available in the Activity tab of the application.
```

**6.** How do you update an app already deployed on Heroku?

<!-- enter you answer in the space below -->

```
If you have Auto-Deploy enabled, you simply need to update the GitHub repository that stores your file.
Else, you'll need to redebeploy the app after making changes to the source code.
```

**7.** Why is branching important to version control?

<!-- enter you answer in the space below -->

```
Cuz I like not ripping my hair out.
It's important to ensure that you do not have conflicts between project pushes, and appropriate branch hygiene is the best way to do that.
```

**8.** When should code review happen?

<!-- enter you answer in the space below -->

```
As a base, when you encounter errors.
Ideally, actively as you push your code on a daily basis.
In practice, when confirming pull requests from the main GitHub.
```

**9.** What is the term used to define combining two branches?

<!-- enter you answer in the space below -->

```
"Merging" branches to the "Master" or "Main"
```
