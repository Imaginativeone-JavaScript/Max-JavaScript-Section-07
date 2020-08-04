# JavaScript - The Complete Guide 2020 (Beginner + Advanced)

## Section 07: Working with the DOM

## 145 Module Introduction

- HTML, DOM & JavaScript
- Nodes & Elements
- Querying DOM Nodes & Traversing the DOM
- Evaluation & Manipulating DOM Nodes
- Creating & Removing DOM Nodes

## 146 What's the DOM?

- HTML Parsed & Rendered by Browser
- JavaScript is a "Hosted Language"
- Browser Exposes Web API to allow JavaScript to work with the parsed document
- DOM = Object Representation of Loaded and Rendered HTML Code

```javascript
const titleEl = document.querySelector("h1"); // select the first h1 HTML Element node
```

- DOM is not strictly tied to Browsers! There are other tools that can parse HTML!
- "document" is the Root DOM Node
- Provides access to element querying, DOM content, etc
- "document" is a property of the "window" object

- "window" reflects the active Browser Window/Tab
- Acts as global storage for script, also provides access to window-specific properties and methods

## 147 Document and Window Object

```javascript
console.log(document); // prints html elements
console.dir(document); // prints DOM Object Property tree

document.element; // HTML element tree

console.log(window); // All the core APIs that the Browser wants to expose to me
console.dir(window); // Both log and dir print the same thing, the Object Property tree
```

## 148

- The Document Object Model (DOM)

```html
<html></html>
```

## 149

## 150
