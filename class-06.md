##### [back-home](https://mhd22.github.io/201-reading-notes)

# Read: 06 - JS Object Literals; The DOM

### _______________________________

## JS Object Literals

- An object is a series of variables and functions that represent something from the world around you.
- as methods of the object.

### _______________________________

## The DOM

- The browser represents the page using a DOM tree.
- DOM trees have four types of nodes:
  1. document nodes,
  2. element nodes,
  3. attribute nodes,
  4. and text nodes.
- You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.
- Whenever a DOM query can return more than one node, it will always return a Nadelist.
- From an element node, you can access and update its content using properties such as textContent and
innerHTML or using DOM manipulation techniques.
- An element node can contain multiple text nodes and child elements that are siblings of each other.

### _______________________________


***TRAVERSING BETWEEN ELEMENT NODES***

*You can move from one element node to a related element node.*

- **parentNode**
  - Selects the parent of the current element node (which will return just one element).

- **previousSibling / nextSibling**
  - Selects the previous or next sibling from the DOM tree.

- **firstChild / lastChild**
  - Select the first or last child of the current element.

### _______________________________

**nodeValue**
- This property lets you access or update contents of a ***text node***.

- One property allows access to child elements and text content: **innerHTML**
- nother just the text content: **textContent**

### _______________________________

### DOM manipulation.

Several methods let you create new nodes, add nodes to a tree, and remove nodes from a tree:

- **createElement()**
- **createTextNode()**
- **appendChild()**
- **removeChild()** 
This is called DOM manipulation.

### _______________________________

ACCESS OR UPDATE ATTRIBUTE VALUES

- **hasAttribute()**  
- **getAttribute()**
- **setAttribute()**
- **removeAttribute()**
The first checks if an attribute exists. The second gets its value. The third updates the value.
The fourth removes an attribute.
### _______________________________

`getElementsByClassName('class');`  ***This method is faster than querySe1ectorA11()*** .

`getElementsByTagName('tag');` ***This method is faster than querySe1ectorA11()***.

### _______________________________
// Change the value of the class attribute.
 **el.className ='cool'** ;

 ### _______________________________

- **innerHTML**   Gets/sets text & markup
- **textContent** Gets/sets text only
- **innerText**   Gets/sets text only

### _______________________________

### This file wrote by [Mohamad Saad Eddin](https://github.com/MHD22).
***you can visit my profile and follow me.***
### __________________________


###### Thanks for your time, I hope that you have enjoyed.
