# In memory storage

## Understanding the JavaScript Call Stack

**1- What is a ‘call’?**

is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

**2- How many ‘calls’ can happen at once?**

only do one thing at a time.

**3- What does LIFO mean?**



**4- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**

When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

**5- What causes a Stack Overflow?**

when there is a recursive function (a function that calls itself) without an exit point.
