# Execution context object
## VO: variable object

## scope chain

## "this" variable
- regular function call: this keyword points at the global object (the window object in the browser)
- method call: this variable points to the object that is calling the method.

this keyword is not assigned a value until a function where it is defined is actually called.

# when a function is called

The argument object is created, containing all the arguments that were passed into the function.

# hosting
- code is scanned for function declarations: for each function, a property is created in VO, pointing to the function.
- code is scanned for variable declarations: for each variable, a property is created in VO, and send to undefined.

