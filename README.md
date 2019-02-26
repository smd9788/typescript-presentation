# TypeScript

## Prerequisites

-  JavaScript basics
-  Knowledge of code compilers

## Objectives

By the end of this, developers should be able to:

-  Describe what TypeScript is and why it is different than JavaScript
-  Identify advantages to using TypeScript over plain JavaScript  

## What is TypeScript?

"TypeScript is JavaScript, TypeScript is just an additional layer of type safety added on top of JavaScript for use when you want it." - [TypeScript: A Love Tale With JavaScript](https://www.youtube.com/watch?v=0siV7xeYSbY&t=1158s)

TypeScript is a programming language based on JavaScript and developed by Microsoft. Per the [TypeScript
doc's](https://www.typescriptlang.org/index.html), "TypeScript is a typed superset of JavaScript that compiles into plain
JavaScript." TypeScript is considered a "transpiler," which is a term
used for a compiler that converts the source code into a language that is structured
similarly and has a similar level of abstraction. That is why TypeScript code will
look almost identical to JavaScript code.

TypeScript is also compatible with almost all JavaScript libraries such as React,
Node, and Angular. It compiles into code compatible with any web browser or any
JavaScript engine (ECMAScript 3 or newer).

## Why use TypeScript?

Main goal of Typescript is to give developers a toolkit that allows us to spend more time writing new code, and less time analyzing,      understanding, and error testing existing code.

### PROS:
  - #### Scalability:
  TypeScript was designed with large applications and large dev teams in mind and can be used on the front end and on the back end.
  - #### Static Typing:
  Be explicit about the data type of variables and function arguments. TypeScript's type checking acts almost as a linter, as it will warn you about potential errors before the code is ran. This concept of static data types is familar to a lot of programmers who code in a language with stricter type checking, like C++ or Java, however using static typing is still optional in TypeScript.

  TypeScript:
  ```
  var message:string = "Hello World" 
  console.log(message)
  ```

  Compiled to JavaScript:
  ```
  var message = "Hello World";
  console.log(message);
  ```
  - #### Error handling:
TypeScript provides a lot of ways to add validations to your JavaScript code. It will throw meaningful default error messages so you don't have to code out error handling messages that are known to cause performance issues.

### CONS:
  - Not natively supported by browsers
  - Add's alot of "extra" code
  - Less flexible than plain JavaScript. Most dev's would say start with JavaScript
    and convert to TypeScript later if you need it's features
    
  ### Unique Features:
  - Static typing
  - Interfaces
  - Classes
  - Declarations
    
## References
- https://www.typescriptlang.org/
- https://github.com/Microsoft/TypeScript/blob/master/doc/spec.md
- https://medium.freecodecamp.org/when-should-i-use-typescript-311cb5fe801b
- https://www.youtube.com/watch?v=0siV7xeYSbY&t=1158s
- https://tutorialzine.com/2016/07/learn-typescript-in-30-minutes
