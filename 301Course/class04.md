# React and Forms


### What is a ‘Controlled Component’?

It can be helpful to have a React component that is reponsible for controlling what happens within a form. A controlled component is an input form element whose value is controlled by React.

`>` This allows for more flexibility down the road, even though it requires more code upfront.

### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?

It depends on what the goal is. But there are situations in which is may be helpful or necessary to have the state update as they type. The potential downside to that may be that the page would re-render, but that can be stopped using prevent default.

### How do we target what the user is entering if we have an event handler on an input field?

We can store event.target.value in state, and modify and access it from there.

___


### Why would we use a ternary operator?
If you have some condition that you are checking that has two potential outcomes, and could fit into the true or false categories, then a ternary operator could be a more efficient way of writing that code.

`>` Structure of ternary operator

`condition ? value if true : value if false`

***Changing if else statements to ternary***

  `if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }`

## =>

  `let result = x===y ? true : false;
  console.log(result);2wdz`