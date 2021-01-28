# javascript-beginner-to-pro
JavaScript beginner to pro. Udemy course

## Output
### innerHTML
Sets the content of the given element
### document.write
Sets the content of the whole document
### window.alert
Displays a window notification with any information
### console.log
Write the information given to the web search engine console.
## Variables
var, let, const.
- var
Is the old way o declare a variable (before ECMAScript 6). They are global and local scoped. They can be updated and re-declared. The hositing moves the variable to the top and initializes it with `undefined`. There is a problem with the re-declaration because you can't notice if you already declared a variable. This brings problem about the value of the variable.
- let
It's the improvement of `var` since ECMAScript 6 creation. They are block scoped. A block is defined by curly braces. They can be updated but not re-declared. Hoisting moves the variable to the top but it's not initialized. You can get a reference error if you try to use it before declaring it.
- const
They are block scoped. They can be neither updated nor re-declared. Hoisting moves the variable to the top but throws an assignation error.

### Variable name rules
1. Variable names can have english letters, numbers, dollar character and underscore only.
2. Variable names can start with english characters only. It can start with dollar sign and underscore (it's not pretty common).
