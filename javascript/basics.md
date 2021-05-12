# Javascript basics
- Originally javascript is designed to run on browers. browsers has a javascript engine to run js files.
- Later Node is constructed as a c++ program which runs chrome's open source js engine called V8 to execute js files.

### What is ECMAScript?
- ECMAScript is otherwise known as ES which is a specification known to set some standard rules in javascript.
- ECMAScript is a specification, where as javascript is a programming language build on top of it.
- ES5/ES6 are terms used to represent ECMA script through versions.

### Most commonly used IDEs for javascript
- Atom(Free)
- VSCode(Free) [Highly Recommended]
- WebStorm(Paid)

### ways to include js code in your HTML File
- add `script` tag in the body tag and write your code.
``` 
<html>
<head></head>
<body>
<script>
console.log("Hello World");
</script>
</body>
</html>
```
- or use `src` property to include js code from `.js` file.

``` 
---index.js---
console.log("Hello World");
---index.html---
<html>
<head></head>
<body>
<script src="./index.js"/>
</body>
</html>

```

### Basic programming paradigm
- console.log
- variables
- conditional statements
- looping statements
- functions
- class

## console.log
- In javascript we use `console.log([---Statement here---])` to log values in browser console. in case of Node it logs in terminal.
