# Get Started

> **Electrode Environment Setup Requirements:**  
> **\* Latest **[**Node LTS binary**](https://nodejs.org/en/)**\(at least v4.2 required\), tip: use **[**nvm**](https://github.com/creationix/nvm) **to manage your nodejs versions. **
>
> **\***[**npm v3**](https://github.com/npm/npm/releases/tag/v3.0.0) **- Install the latest **[**npm**](https://www.npmjs.com/) **version**`install-g npm`
>
> please checkout [requirements docs](http://www.electrode.io/docs/requirements.html) for detailed setup instructions.

## Quick Guide

Are you ready to build your first Electrode App?

Please make sure to have all the [environment requirements](http://www.electrode.io/docs/requirements.html) ready & setup before proceeding to the next step.

First, install [Yeoman](http://yeoman.io/) and the [Electrode Generator](https://github.com/electrode-io/electrode#yeoman-generator).

```
$ npm install -g yo gulp generator-electrode

** NOTE: You may need sudo depending on your machine permissions. **
```

Make a new directory for your awesome app, the generate your new project:

```
$ mkdir your-awesome-app
$ cd your-awesome-app
$ yo electrode
```

Fill out the Electrode App generator with your information:

![](http://www.electrode.io/img/generator-application.png)

Run one simple command to start the server. Presto!

```
$ gulp dev
```

Now open [localhost:3000](http://localhost:3000/) in your browser to access the app. Hello Electrode!

To view all the gulp tasks available type`gulp`. To build your app's client bundle for production use.

```
gulp build
```



