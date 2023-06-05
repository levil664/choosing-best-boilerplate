# **Testing and learning patterns to choose the best for next-redux.**

The branches in this project are named according to their technologies and project names.
For example: [canary-next-redux-boilerplate](https://github.com/levil664/choosing-best-boilerplate/tree/canary-next-redux-boilerplate) is a branch.
Where [canary](https://github.com/vercel/next.js/tree/canary) is the boilerplate provided by the development team [Next.js](https://github.com/vercel/next.js).
next-redux talks about a bundle of technologies that demonstrates the use of [redux](https://github.com/reduxjs) in conjunction with [Next.js](https://github.com/vercel/next.js) in the project.

## Here are the main pros and cons of these templates:

### canary-next-redux-boilerplate:
This example is from Next.js provides basic Redux integration into the application Next.js . It includes setting up a Redux store, examples of using Redux in components, and shows how to use server rendering with Redux.

**pros:**
- Server rendering: Next.js provides support for server rendering out of the box, and this example shows how to use Redux together with server rendering. This allows you to optimize the performance and improve the SEO of your application.
- Project Structure: The example suggests a good project structure that divides the code into components, pages, and Redux actions. This helps to keep your code clean and organized.
- There are a couple of ready-made examples and files for testing.
- There are examples of thunks, including asynchronous ones.  There are also a lot of comments written for them, thanks to which their work is clear.
- The deploy is done using the vercel [user interface](https://vercel.com/new/clone?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-redux&project-name=with-redux&repository-name=with-redux).

**cons:**
- Additional Dependencies: When using Redux, as in this example, you will also need to install and configure additional dependencies. This can add complexity to the project setup and increase the size of the project.
