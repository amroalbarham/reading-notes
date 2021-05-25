# In memory storage

- **What is a ‘call’?**

***At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).***

- **How many ‘calls’ can happen at once?**

    1. ***When secondFunction() gets executed, an empty stack frame is created. It is the main (anonymous) entry point of the program.***
    2. ***secondFunction() then calls firstFunction()which is pushed into the stack.***
    3. ***firstFunction() returns and prints “Hello from firstFunction” to the console.***
    4. ***firstFunction() is pop off the stack.***
    5. ***The execution order then move to secondFunction().***
    6. ***secondFunction() returns and print “The end from secondFunction” to the console.***
    7. ***secondFunction() is pop off the stack, clearing the memory.***

- **What does LIFO mean?**
 ***When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.***

 - **What causes a Stack Overflow?**

 ***A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.***


 ## JavaScript error messages

 - **What is a ‘refrence error’?**

 ***The first thing that indicates you that something is wrong with your code is the (in)famous error message that the one we saw just moments ago, it usually appears on your console (being developer tools of the browser, terminal or whatever else you are using).***

 - **What is a ‘syntax error’?**

***I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.***

- **What is a ‘range error’?**

***Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.***

- **What is a ‘type error’?**

***It is an error that show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.***

- **What is a breakpoint?**

***You can also add conditional breakpoints by right-clicking a previous set breakpoint, which will make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values.***

- **What does the word ‘debugger’ do in your code?**

***I’ve added a debugger statement and when running the code above you can see the “history” before reaching that breakpoint.***



