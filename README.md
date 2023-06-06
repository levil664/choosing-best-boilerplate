# **Testing and learning patterns to choose the best for next-redux.**

The branches in this project are named according to their technologies and project names.
For example: [canary-next-redux-boilerplate](https://github.com/levil664/choosing-best-boilerplate/tree/canary-next-redux-boilerplate) is a branch.
Where [canary](https://github.com/vercel/next.js/tree/canary) is the boilerplate provided by the development team [Next.js](https://github.com/vercel/next.js).
next-redux talks about a bundle of technologies that demonstrates the use of [redux](https://github.com/reduxjs) in conjunction with [Next.js](https://github.com/vercel/next.js) in the project.

## Here are the main pros and cons of these templates:

### canary-next-redux-boilerplate:
[This example](https://github.com/vercel/next.js/tree/canary/examples/with-redux) is from Next.js provides basic Redux integration into the application Next.js . It includes setting up a Redux store, examples of using Redux in components, and shows how to use server rendering with Redux.

**pros:**
- Server rendering: Next.js provides support for server rendering out of the box, and this example shows how to use Redux together with server rendering. This allows you to optimize the performance and improve the SEO of your application.
- Project Structure: The example suggests a good project structure that divides the code into components, pages, and Redux actions. This helps to keep your code clean and organized.
- There are a couple of ready-made examples and files for testing.
- There are examples of thunks, including asynchronous ones.  There are also a lot of comments written for them, thanks to which their work is clear.
- The deploy is done using the vercel [user interface](https://vercel.com/new/clone?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-redux&project-name=with-redux&repository-name=with-redux).

**cons:**
- Additional Dependencies: When using Redux, as in this example, you will also need to install and configure additional dependencies. This can add complexity to the project setup and increase the size of the project.

### kirill-konshin-next-redux-wrapper:
[This boilerplate](https://github.com/kirill-konshin/next-redux-wrapper/discussions) offers Redux integration into Next.js using the next-redux-wrapper library. It provides a simple Redux setup and provides usage examples in components Next.js.

**pros:**
- A very voluminous, heavy template, but this is compensated by the availability of detailed documentation.
- Very well suited for giant projects.
- Examples for redux, redux-toolkit and many other demo pages.

**cons:**
- Difficult to deploy.
- The file system is difficult to master.
- Too big for small-sized and medium-sized projects.

### nextjs-with-redux-and-material-ui-master:
[In this example](https://github.com/joaopaulomoraes/nextjs-with-redux-and-material-ui), we will display a counter that is initialized with a value of 0 and will be updated with each click. The first rendering is happening on the server, then the browser takes over. To illustrate this, the rendered counter will have a value of 1 when the app loads and a flag with the dispatch source will be displayed above the counter. From the next clicks that increment / decrement, the counter will receive its new value and the flag with the origin will be updated again with the origin of the dispatch.

**pros:**
- Uses material-ui, this makes it easier to develop.
- An easy-to-understand project if you have already been developing with the help of next and react.
- Has an example of SSR (server site rendering).
- Has an example of requests with redux.

**cons:**
- Has no documentation and comments.
- Project has only js files, don't support ts.
- Has small pull of examples.
