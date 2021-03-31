## The Call Stack and Debugging
### The Call Stack

- A call stack is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions what function is currently being run and what functions are called from within that function .

- a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

- Last In, First Out (LIFO) principle, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

- When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.

- Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.

- When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.

- If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

- In summary, then, we start with an empty Call Stack. Whenever we invoke a function, it is automatically added to the Call Stack. Once the function has executed all of its code, it is automatically removed from the Call Stack. Ultimately, the Stack is empty again

### Reference errors
This is as simple as when you try to use a variable that is not yet declared you get this type os errors.
when using const and let, they are hoisted like var and function but there is a time between the hoisting and being declared so when you try to access them a reference error occurs, is called Temporal Dead Zone.

### Syntax errors
This occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.