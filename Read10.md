# JS: Error Handling & Debugging


**Debugging is a process of testing and finding errors and reducing their occurrence in the future.**

`>>` This requires that you understand the context of the implementation of your program to discover errors in it


**The console is a great helper in minimizing the area where the error is, so that you can try to find the exact error.**

![console](https://miro.medium.com/max/2100/1*LHpmsxV3f2znpxhuAFuIqA.png) 

---

*JavaScript contains ***7*** different types of errors. Each creates its own error object, which can tell you its line number and provide a description of the error.*


1. `RangeError`:

    This is thrown when a number is outside an allowable range of values.

2. `ReferenceError`:

    This error is thrown when a reference made to a variable/item is broken. That is the variable/item doesn’t exist.

3. `SyntaxError`:

    This is the most common error we encounter. This error occurs when we type code that the JS engine can understand.

4. `TypeError`:

    TypeError is used to indicate an unsuccessful operation when none of the other NativeError objects are an appropriate indication of the failure cause.

5. `URIError`:

    This indicates that one of the global URI handling functions was used in a way that is incompatible with its definition.

6. `EvalError`:

    This is used to identify errors when using the global eval() function.

7. `InternalError`:

    This error occurs internally in the JS engine, especially when it has too much data to handle and the stack grows way over its critical limit. 


`>>` If you know you might get an error, you can safely handle it with ***try, catch***, and finally statements. Use it to provide users with helpful feedback.

![try](https://javascript.info/article/try-catch/try-catch-flow.svg)