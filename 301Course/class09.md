# Functional Programming

## What is functional programming?
It is a paradigm, like object-oriented programming. It is a style for how to code is built and organized. It avoids changing-state and mutable data.

## What is a pure function and how do we know if something is a pure function?
A function is pure if...

It returns the same result w/same arguments deteministic
No observable side effects
No external objects being used within the function
No reading of external files
No use of the number generation methods
What are the benefits of a pure function?
If the value of a global variable changes, and is also used within the function, the result may not be as expected. This is avoided with a pure function. The code is also easier to test.

## What are the benefits of a pure function?
`>` 
In computer programming, a pure function is a function that has the following properties: The function return values are identical for identical arguments (no variation with local static variables, non-local variables, mutable reference arguments or input streams).

* Easier to reason about
* Easier to combine
* Easier to test
* Easier to debug
* Easier to parallelize

## What is immutability?
immutability: the state cannot be changed after it has been created. Changing an immutable object can't be done, so you create a new object with the new value. For example- using a for loop to create a new array.

## What is Referential transparency?
referential transparency: this is what happens when you have pure functions and immutable data. So, for example, if one replaced a function with a number that the function would always result to, that would give it referential transparency.

---
## **Node JS**

## What is a module?
A chunk of code that has a specific job to do, that should be able to be called upon when the job needs to be done.

## How do we bring another module into the file the we are working in? What does the word ‘require’ do?
We use Require to point to a path to a js file. The .js ending is not necessary. e.g.--> require(./'count'); This is the first step in making that code able to function inside the module. Next, you have to make it available to use.

## What do we have to do to make a module available?
Inside the initial module, one should specify what about the code should be able to be accessed outside the module. In the module `-->` module.exports =functionname; Then one should go back and set the function name equal to the require statement.

## How do we bring another module into the file the we are working in?

To include functions defined in another file in Node.js, we need to import the module. we will use the require keyword at the top of the file.

The result of require is then stored in a variable which is used to invoke the functions using the dot notation.

`>` This is the way imports work. When you import something for the first time, the file is run and the exported values from it are returned back to the one importing it. When something is imported again, those same exports are reused and returned. Node JS modules work the same way.
