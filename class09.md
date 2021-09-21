# FUNCTIONAL PROGRAMMING

## Functional Programming Concepts

**1- What is functional programming?**

Functional programming is a programming paradigm — a way of constructing the structure and parts of computer programs — that regards computation as the evaluation of mathematical functions and eliminates mutable data and changing states.

**2- What is a pure function and how do we know if something is a pure function?**

When learning functional programming, the first essential notion we learn is pure function.

An dwe can know if the function is a pure or not, by:

* It returns the same result if given the same arguments.
* It does not cause any observable side effects.

**3- What are the benefits of a pure function?**

* The code’s definitely easier to test.
* We don’t need to mock anything.

**4- What is immutability?**

When data is immutable, it can't change its state once it's been produced. It is impossible to alter an immutable object. Instead, you make a new object and assign the new value to it.

**5- What is Referential transparency?**

In functional programming, this is a term you'll hear a lot. It signifies that the result of an expression can be used instead of the expression itself.
