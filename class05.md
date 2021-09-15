# Putting it all together

## React Docs - Thinking in React

1- What is the single responsibility principle and how does it apply to components?

A component should ideally perform only one function. It should be divided into smaller subcomponents if it grows.

2- What does it mean to build a ‘static’ version of your application?

Rather than relying on server-side technologies, all HTML, CSS, and JavaScript rendering is done on the client side.

3- Once you have a static application, what do you need to add?

When generating our static app, we'll need to change the build directory to dist/ and use the npm run build command.

4- What are the three questions you can ask to determine if something is state?

* Is it passed in from a parent via props?
* Does it remain unchanged over time?
* Can you compute it based on any other state or props in your component?

5- How can you identify where state needs to live?

* Determine which components render something depending on that state.
* Look for a component with a common owner (a single component above all the components that need the state in the hierarchy).
* The state should be owned by either the common owner or another component further up in the hierarchy.
* If you can't find a component that makes sense to own the state, develop a new component dedicated to retaining the state and place it above the common owner component in the hierarchy.
