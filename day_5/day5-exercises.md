# Day 5 Exercises
## Statements, Variables, Data Types, & Arrays

1. How do you declare a variable. What does the equals sign really mean in JavaScript? What is it called in JavaScript?
- A variable is declared by using a variable keyword (or identifier), assigning a variable name and terminating with a semicolon. Example: `var name;`
- The equals sign is used for variable assignment and is called the assignment operator.

2. There are three big data types in JavaScript: numbers, strings, and booleans. Describe what each of them are.
- Numbers - this data type is used for handling numerical values
- Strings - this data type consists of letters and other characters
- Booleans - this data type has one of two values: true or false

3. What are the six rules for naming variables? What are a few JavaScript reserved words that you should avoid using for variable names?
- Variable names:
  * Must begin with a letter, dollar sign or an underscore, but not a number
  * Can contain letters numbers, numbers, dollar sign, or an underscore - however, no dash or period
  * Cannot contain keywords or reserved words (ie: `var`, `for`, `char`, `while`)
- Are case sensitive (bad practice to create two variables with same name with different cases)
- Should use a name that describes the information contained in the variable store
- Should use camel case if using more than one word - lowercase first word, uppercase second word (ie: firstName, coolCars)

4. How can an array be useful when dealing with multiple related values? How do you access/change a value in an array?
- An array can be useful when the number of list items is unknown - when created the number of values does not need to be specified
- An array value can be changed by selecting it and assigning it a new value, much like any other variable. (ie: `cars[0] = "Honda";`)

5. What is the difference between an expression and a statement?
- Expressions evaluate into a single value and rely on operators to calculate a value
- Statements are individual instructions or steps in a script; should in with a semicolon

6. What are three types of operators and how are they used?
- Assignment operators - used to assign value to a variable (ie: `color = "blue";`)
- String operators - used to combine two strings (ie: `fullName = "Son " + "Goku";`)
- Comparison operators - used to compare to expressions and return true or false (ie: `purchase = 5 > 10;`)
