# Day 6 Exercises
## Functions & Scope

1. If we have a function defined as function sayHello(){console.log("Hello!")}, what is the difference between entering sayHello and sayHello() in the console?
- In the developer console:
  * `sayHello` displays the the function, resulting in `ƒ sayHello(){console.log("Hello!")}`
  * `sayHello()` calls the function , resulting in `Hello!`

2. What is the difference between function parameters and arguments?
- Function parameters are used when a function needs specific information to perform its task - in these cases when the function is declared, parameters are given. Inside the function, the parameters act like variables.
- Function arguments are used when a function is called that has parameters - the values it should use should be specified in the parentheses that follow its name. These values are called arguments and can be provided as values or variables.

3. What is the keyword return used for?
- The return keyword is used to tell the interpreter to leave the function and go back to the statement that called it.

4. How are local variables better than global variables? Are there instances you can think of where you might want to use a variable that is globally scoped over local?
- Local variables:
  * Use less memory
  * Decrease the risk of variable naming conflicts
  * Can have different values if the function runs twice
- If a variable needs to be used in more than one function, then a globally scoped variable should be used.
