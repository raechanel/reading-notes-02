# Object Literals and DOM

***

## Object Literals

What is an object? Objects group together a set of variables and functions to create a model of somethinng you would recognize from the real world. In an object, variables and functions take on new names.

***In an object: Variables become known as properties and functions become known as methods***

Example:

`let person = {`

`    name: 'alexis',`

`    age: '28',`

`    birth month: 'september',`

`    intrests: 'traveling', ['swimming', 'reading', 'social media'],`

`}`


**The object is person**

| Properties: `Key` | Properties: `Value`   |
| ---------         | ------------          |
| name              | string                |
| age               | number                |
| birth month       | string                |
| siblings          | boolean               |
| intrest           | array                 |


***

# DOM

What is DOM? Dom is the Document Object Model. This specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a webpage while in a browser window.

When the browser loadsa web page, it creates a model of the page to memory.

The DOM specifies the way in which the browser should structure this model using a `DOM tree`.

The DOM is called an objetct model because the model (the DOM tree) is made of objects

Each part represent a different part of the page loaded in the browser window

The DOM tree is a model of a web page

DOM trees have four types of nodes: `document nodes`, `element nodes`, `attribute nodes`, and `text nodes`. 
