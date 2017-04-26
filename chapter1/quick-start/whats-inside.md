# What's Inside

#### Explore More

What does `generator-electrode` give you? Let's go through the most important files to understand the structure of your new app.

> &lt;your-awesome-app&gt;/src/client/components/home.jsx

This is the home React component for your app. [React](https://facebook.github.io/react/index.html) is a JavaScript library for building user interfaces. A simplified way to look at React is that it can be used as the _View_ in a _Model-View-Controller_ application. It was created by Facebook and is being actively developed.

Building with React lets developers create a modular and reusable component architecture. We can then reuse the business logic in existing _models_ and _controllers_ because React components encapsulate only the view layer. The components you write are self-contained, which aids developers in quickly determining what a component does directly by reading the source. Finally, it is ideally suited to Universal JavaScript \(previously called Isomorphic JavaScript\), the practice of sharing code between the server and the client.

> &lt;your-awesome-app&gt;/src/client/styles/base.css

We will use [CSS Modules](https://github.com/css-modules/css-modules): a CSS file in which all class names and animation names are scoped locally by default. At WalmartLabs, this helps us tackle large-scale styling requirements by mitigating the issues inherent in the global scope in CSS.

> &lt;your-awesome-app&gt;/src/client/styles/app.jsx



