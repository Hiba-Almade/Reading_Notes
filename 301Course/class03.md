# Lists and Keys in React


### What does .map() return?

`.map()` will return a new array.

___
### If I want to loop through an array and display each value in JSX, how do I do that in React?

You can place the variable that is being added to the array within curly brackets, within a JSX tag. For example: `<li>{value}</li>`



____

### What is the purpose of a key?

Each list item needs a unique key.

Keys signal to react which elements are which, and help keep track of when items are removed or added. You can add an id as the index when mapping through an array, for example. But only if the order of the items will not change. You can also use the id that is on the individual item of data.

____
___

## Spread Operator

### What is the spread operator?
The spread operator is three dots that expands an object into a list of arguments.

___
### List 4 things that the spread operator can do.
* It can take values in an array and separate them out to make it easier to run methods such as Math.max.
* You can use it to copy or combine arrays
* It helps you use arrays as arguments
* A good tool to add items to lists
