# Why Use Electrode?

> If you're writing a universal React/Node.js application, then Electrode is for you!

At [@WalmartLabs](http://www.walmartlabs.com/), we recently migrated [walmart.com](http://walmart.com/) to a [Universal JavaScript](https://medium.com/@mjackson/universal-javascript-4761051b7ae9#.k3j9fruyn) stack using React/Node.js. Along the way, we hit a few stumbling blocks that might sound familiar if you've worked on a large, complex web app before.

### Universal JavaScript

Universal JavaScript allows us to use the same view rendering code from the server and client. When a user requests a page, they immediately receive the fully rendered HTML on initial page load. They will not have to wait for the client side JavaScript code to load and render the page.

Rich app like experiences are possible without requiring a full page load when navigating or responding to user actions within the same page. The client side code will handle all the rendering of the view changes within the page. Only the data changes will be sent between the client and the server.

This approach provides for an optimized user experience resulting in fast page loads and even faster navigation experience. In the world of eCommerce where every millisecond counts, we believe this is the best way forward.

### Code/UI Reuse

We reuse React components across all of our brands, which means our developers need to be able to search through thousands of components, view their documentation and see them rendered, and use another developer's component secure in the knowledge that its structure and implementation are consistent with our standards. We needed a way to ensure that all components were built according to modern best practices, without slowing our developers down with a lot of manual configuration.

### Server Side Rendering \(SSR\) Performance

We serve millions of customers a day, so performance is critical to our business. React's SSR support is vital for SEO \(Search Engine Optimization\) and has the potential to improve performance, but it's intensive on the server CPUs. We needed a platform with SSR built-in with a default configuration that's optimized for performance.

### Fast Startup and Deployment



