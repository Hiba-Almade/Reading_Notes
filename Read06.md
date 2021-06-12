# JS Object Literals; The DOM


## **JS Object Literals:**
An object is a series of variables and functions that represent something from the world around you.
as methods of the object.

`>>` A JavaScript object literal is a comma-separated list of name-value pairs wrapped in curly braces. Object literals encapsulate data, enclosing it in a tidy package. This minimizes the use of global variables which can cause problems when combining code.

![Ob](https://mathiasbynens.be/_img/js-engines/object-model.svg)

---

## **The DOM:**
The browser represents the page using a DOM tree.

DOM trees have *four* types of nodes:

 * document nodes
 * element nodes
 * attribute nodes
 * text nodes

You can select element nodes by their `id` or `class` attributes, by `tag name`, or using CSS `selector` syntax.

![dom](https://www.guru99.com/images/JavaScript/javascript8_1.png)


### ACCESS OR UPDATE ATTRIBUTE VALUES:

`hasAttribute()` checks if an attribute exists
`getAttribute()` gets its value
`setAttribute()` updates the value
`removeAttribute()` removes an attribute.


> `el.className ="newClassName"`  Change the value of the class attribute

