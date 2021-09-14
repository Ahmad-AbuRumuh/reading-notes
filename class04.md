# React and Forms

## React Docs - Forms

**1- What is a ‘Controlled Component’?**

When a React component renders a form, it also controls what happens in that form when the user enters data.

**2- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

I think the better is wait him to submit, because maybe he change the answer or choose one by mistake. So the better for him and us is to wait.

**3- How do we target what the user is entering if we have an event handler on an input field?**

By using target.value in the input.

## The Conditional (Ternary) Operator Explained

**1- Why would we use a ternary operator?**

If the condition is true, you can assign one value to the variable; if the condition is false, you can assign another value.

2- Rewrite the following statement using a ternary statement:

```javascript
 if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
```

ternary statement:

```javascript
let isTrue = x === y ? truse : false
```
