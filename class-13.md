##### [back-home](https://mhd22.github.io/201-reading-notes)

# Read: 13 - Local Storage

### _______________________________

## INTRODUCING HTML5 STORAGE

- “HTML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” 

- It’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually), it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

- From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object.

- HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.

- However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like `parseInt()` or `parseFloat()` to coerce your retrieved data into the expected JavaScript datatype.

### _______________________________

### USING HTML5 STORAGE:

- To store item: `localStorage.setItem('key',value);`
OR :             `localStorage['key']=value;`

- To get item: `var data = localStorage.getItem('key');`
OR :           `var data = localStorage['key'];`

### _______________________________

### This file wrote by [Mohamad Saad Eddin](https://github.com/MHD22).
***you can visit my profile and follow me.***
### __________________________


###### Thanks for your time, I hope that you have enjoyed.
