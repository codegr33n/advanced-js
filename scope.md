## Types of scopes

1. ### Block Scope
    Variables declared inside a pair of curly braces cannot be accessed from outside the block

2. ### Function scope
    Variables defined inside a function cannot be accessed from outside the function

3. ### Global scope 
    Variables defined in the global scope, can be accessed in a block or function


## Lexical scoping
This is a way javascript resolves variable names, when functions are nested. The way it does this, is by first looking at the innermost function in search for the variable name, and moves one level up if the name is not found, until it get's to the global scope.