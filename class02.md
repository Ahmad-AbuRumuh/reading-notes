# React lifecycle

1- **Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**

The render happens before the componentDidMount.

2- **What is the very first thing to happen in the lifecycle of React?**

The first thing is mounting.

3- **Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates.**

* constructor
* render
* componentDidMount
* React Updates
* componentWillUnmount

4- **What does componentDidMount do?**

load anything using a network request or initialize the DOM.

## React State Vs Props

1- **What types of things can you pass in the props?**

We can transmit values from the parent component to the child component using this method. Any data type can be used as a value.

2- **What is the big difference between props and state?**

Props are controlled outside of a component, whereas state is managed inside it.

3- **When do we re-render our application?**

Anytime their state or props change.

4- **What are some examples of things that we could store in state?**

The user changes in the value to re-render the page.
