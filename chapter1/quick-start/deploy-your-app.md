# Deploy Your App

We're almost finished with our Quick Start. The final step is to deploy `your-awesome-app` and share it with your fellow developers using [Heroku](https://devcenter.heroku.com/categories/deployment). We have listed the steps below, but feel free to learn more about Heroku [here](https://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction). These instructions assume you have a GitHub account. Navigate to your GitHub and create a new empty repo 'Your-Awesome-App'. Hit the `clone your-awesome-repo` and follow the steps below in order:

```
$ git init
$ git add .
$ git commit -m 'first commit'
$ git remote add origin https://github.com/your-Github-name/your-awesome-app.git
$ git push -u origin master
```

Navigate to the [Heroku site](https://signup.heroku.com/dc) and set up a free account. This will help streamline our deployment process \(we will do this several times\).

Next, let's quickly deploy `your-awesome-app` from the command line. \[Click here\]\([https://devcenter.heroku.com/articles/getting-started-with-nodejs\#set-up](https://devcenter.heroku.com/articles/getting-started-with-nodejs#set-up)"\) to download and install the Heroku CLI for your machine.

When you are finished installing, log in using the email address and password you used when creating your Heroku account.

```
$ heroku login
```

Enter your Heroku credentials:



