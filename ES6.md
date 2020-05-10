# Modern Java Script For react 

## ES6 Features 
- Variables creation using "let" and "const"
- Template String 
- Arrow Functions 
- Rest and Spread Operator 
- Destructing 
- Array Functions: find() and FindIndex()
- Classes 
- Promises 
-  ... 

- Some ES6 code is not compatible with some brosers for this reason we use preprocessor like Babel to handle this problem.

- **[Babel](https://babeljs.io/)** is a preprocessor for JavaScript/ECMAScript. It is mainly used to convert ES6+ code into a backwards compatible version of JavaScript that can be run by older browsers. 

## 1. Variable Creation using "let" and "const"
ES6 introduces 2 new ways to create variables. They do not allow hoisting. The benific of this is to reduce errors.

- **let**: It is like a replacement for var. 
    ```
    let name="Dina";
    let age=24;
    ```
- **const** It is used to create vars with constant values. The vars created using const cannot be updated later in the code.
    ```
    const API_URL = "https://google.com";
    ```
## 2. Template String 
It is a string that allow embedding expression inside it. To create a template string you should use back tick instead sigle or double quotes. The expressions are ambedded by wrapping them inside `${}`
for ex: 
```
const greeting = `Hello ${name}`
const gretingf = `Hello ${fullName()}`
``` 
## 3.Arrow Function 
ES6 gives a new syntax for defining functions using fat arrow. Arrow function bring a lot of clarity & code reduction. 
Syntax:
``` 
function greetings(name){
    return('Welcome' + name);
}
// becomes
const greetings = (name) => {
    retun(`Welcome ${name}`)
}
``` 
- If we have only one variable we can remove the paretheses 
```
const greetings = name => {
       retun(`Welcome ${name}`)
}
```
- if we have one statment we can remove the curly braces and no need to return statment 
```
const greetings = name => `Welcome ${name}`
```

## Credits 
All credits goes for this very nice course about ES6: https://www.edyoda.com/course/1500.