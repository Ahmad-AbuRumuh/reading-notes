# Introduction to React and Components

## Component Based Architecture

### What is a component?

A component is a well-defined set of modular, portable, replaceable, and reusable functionality that encapsulates and exports its implementation as a higher-level interface.

A component is a software object that encapsulates specific functionality or a group of functionalities and is designed to interact with other components. It has a clearly defined interface and follows a specified behavior that other components in an architecture should follow.

### What are the charactistics of a component?

* **Reusability**: Components are typically built to be utilized in a variety of contexts and applications. Some components, on the other hand, may be tailored to a specific purpose.
* **Replaceable**: Components can be swapped out for others that are similar.
* **Not context specific**: Components are made to work in a variety of locations and situations.
* **Extensible**: To provide new behavior, a component can be extended from existing components.
* **Encapsulated**: The interfaces that allow the caller to use the functionality of the component are shown, but no details of the internal processes, variables, or state are shown.
* **Independent**: Components are designed to have as few dependencies as possible.

### What are the advantages of using component based architecture?

* **Ease of deployment**: It's easier to replace existing versions as new compatible versions become available, with no impact on other components or the system as a whole.
* **Reduced cost**: You may spread the expense of development and maintenance by using third-party components.
* **Ease of development**: Components use well-known interfaces to offer defined functionality, allowing development to take place without affecting other elements of the system.
* **Reusable**: The utilization of reusable components allows for the expense of creation and maintenance to be shared across multiple applications or systems.
* **Modification of technical complexity**: Through the usage of a component container and its services, a component modifies the complexity.
* **Reliability**: Because the reliability of each individual component improves the overall system's reliability through reuse, the overall system's dependability improves.
* **System maintenance and evolution**: The implementation is simple to tweak and update without affecting the rest of the system.
* **Independent**: Connectivity of components that is both independent and adaptable. Different groups develop components independently and in concurrently. Productivity in software development, both now and in the future.

## What is Props and How to Use it in React

### What is props short for?

React is a component-based technology that breaks down the user interface into smaller, reusable chunks. In some circumstances, those components will need to communicate (transfer data to one another), and the best method to do so is to use props.

### How are props used in React?

Props are mostly used to transmit data between parent and child components. It encourages us to reuse components and cut down on redundancy. However, as a growing app, you may encounter a lot of typechecking bugs.

There is a built-in functionality in React that is used to check the basic validations during typechecking with PropTypes.

### What is the flow of props?

The flow of the props is a uni-directional flow. (one way from parent to child).
