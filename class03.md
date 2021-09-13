# Passing Functions as Props

## React Docs - lists and keys

1- What does .map() return?

New array

2- If I want to loop through an array and display each value in JSX, how do I do that in React?

We loop by array of numbers using the JavaScript map() function. then we return a `<li>` for each item.

3- Each list item needs a unique ____.

Key

4- What is the purpose of a key?

React uses keys to identify items that have been updated, added, or remoted.

## The Spread Operator

1- What is the spread operator?

The Spread operator expands an iterable, such as an object, string, or array, into its elements, whereas the Rest operator reduces a set of elements into one array.

2- List 4 things that the spread operator can do.

* Combine Two Objects
* Combine Arrays
* Copying Arrays
* Get the Maximum Value of an Array

3- Give an example of using the spread operator to combine two arrays.

```javascript
let thisArray = ['sage', 'rosemary', 'parsley', 'thyme'];

let thatArray = ['basil', 'cilantro', ...thisArray, 'coriander'];
```

4- Give an example of using the spread operator to add a new item to an array.

```javascript
const original = ['zero', 'one'];
const newArray = ['two', ...original;
```

5- Give an example of using the spread operator to combine two objects into one.

```javascript
let employee = { name:'Jhon',lastname:'Doe'};
const salary = { grade: 'A', basic: '$3000' };
const summary = {...employee, ...salary};
```

## How to Pass Functions Between Components

1- In the video, what is the first step that the developer does to pass functions between components?

map function

2- In your own words, what does the increment function do?

returns a value after increments its operand.

3- How can you pass a method from a parent component into a child component?

* Create a callback function in the parent component. This callback function will get the data from the child component.
* Pass the callback function in the parent as a prop to the child component.
* The child component calls the parent callback function using props.

4- How does the child component invoke a method that was passed to it from a parent component?

The changeName() method should be passed as a prop to the child component, and it should be accessed as props data within the child component.
