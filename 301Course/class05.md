# Putting it all together:

## How would you break a mock into a component heirarchy?

Use the same techniques for deciding if you should create a new function or object. One such technique is the single responsibility principle, that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

## What is the single responsibility principle and how does it apply to components?

As the name suggests, this principle states that each class should have one responsibility, one single purpose. This means that a class will do only one job, which leads us to conclude it should have only one reason to change.

`>`  For example, if we have a class that we change a lot, and for different reasons, then this class should be broken down into more classes, each handling a single concern. Surely, if an error occurs, it will be easier to find.



## What does it mean to build a ‘static’ version of your application?

Static applications and websites render in the user’s browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies. 
> Static apps are simpler, quicker to develop, and cheaper to host.

## Once you have a static application, what do you need to add?

You need to add values that are dynamic (stored in state) so that things can actually change based on user interaction.

## What are the three questions you can ask to determine if something is state?

* Is it passed in from a parent via props?
* Does it remain unchanged over time?
* Can you computer it based on any other state or props in your component?