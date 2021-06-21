# Local Storage

## HTML5 STORAGE:

**“HTML5 Storage” It is a simple client side database.** 

`>>` Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.”

It’s a way for web pages to store named **key/value** pairs locally, within the client web browser.`->` Like cookies.

Then you can retrieve that data with the same key. 

 The data is actually stored as a string. If you are storing and retrieving anything other than strings
 

**This data persists even after you:**

* Navigate away from the web site 
* Close your browser tab 
* Exit your browser, or what have you.

---


`>>` ***How I can access HTML storage?***

From your JavaScript code, with the localStorage object on the global window object.

`>>` ***How I can store Item?***

 `localStorage.setItem('key',value);` 

OR : `localStorage['key']=value;`

`>>` ***How I can get item ?***

`var data = localStorage.getItem('key'); `

OR : `var data = localStorage['key'];`

![html5](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSSVki8KgBhr7yfMTOPW7Dw8Hb7tXoIAs8elw&usqp=CAU)