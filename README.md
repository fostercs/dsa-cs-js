# DSA & CS with JS

#### Learning Data Strucutres and Algorithims and Computer Science Fundamentals with JavaScript

JS is a imperative and structured scripting language that often requires transpiling; JS both weakly and dynamically typed. For this course we will target ES6. Why ES6? Because ES6 includes everything from Stage 4 in ES2015, and, because of that, we won't need to get into transpiling for these exercises. 

We are not targeting ES5, since ES5 is effectivly ES2009, but ES7+ is intentially not covered in this course for the purposes of organizing those concepts in later materials in accordance with the learning path that is established in this course.

# What is not covered?

- FP in JS

### Beyond ES6

- Scope
- Advanced Flow Control
- ES5 & ES6
- Advanced Functions
- Advanced Arrays
- Advanced Objects
- ES7
- ES8
- Async/Await
- ES9
- ES10
- Advanced Loops
- ES11
- `globalThis`
- ES12
- Debugging
- Modules

### ES7

- The exponentiation operator base ** exponent
- Array includes array.includes(myItem) 		// true or false

### ES8

- Object.entries / Object.values (Array’s values / key equivalence for objects)
- String padding myString.padStart(2); 			// or padEnd
- Trailing comma function test(a,b,c, ) 		// notice the comma after c
- Atomics and shared memory

### ES9

- Lifting template literal restriction.         // Now allow complicated syntax (ex: LaTex) to be used in templates
- Asynchronous iterators                        // Makes it possible to use iterator for async operations like reading a HTTP stream as well as the introduction of for-wait-of
- Promise.finally                               // https://github.com/tc39/proposal-promise-finally
- Object destructuring                          // Reminder for non-React developers: It allows you to: myNewObject = {a,b,c, …object}
- Unicode escape and improvements to Regexes

### ES10

- Array.flat: [[1,2],3]).flat()                 // [1,2,3] equivalent of map().flat()
- Object.fromEntries                            // Reverse operation from Object.entries
- String.trimStart() & String.trimEnd()         // Remove extra spaces in a string
- Optional Catch binding:                       // Remove the need to add a param to the catch
- Function.toString has been revisited to have a consistent behaviour 🥳🥳🥳
- Symbol Description
- BigInt — arbitrary large numbers
- Improvement on Unicode support for JSON.stringify()
- Array.sort now retains order if keys are equal

### ES11

### ES12

### ES13

### ES.Next

# What is covered?

### Foundations

- Javascript Engine
- Call Stack & Memory Heap
- Stack Overflow
- Garbage Collection
- Memory Leaks
- Single Threaded
- JS Runtime
- NodeJS
- Execution Context
- Lexical Environment
- Hoisting
- Function Invocation
- `arguments` Keyword
- Variable Environment
- Scope Chain
- [[scope]]
- Function Scope vs Block Scope
- Dynamic Scope vs Lexical Scope
- Global Variables
- `this` Keyword
- Context vs Scope

### JS Basics

- Variables (CONST and LET replace VAR)
- Control Flow
- Functions
- Arrays (Data Structure)
- Objects (Data Structure)
- Loops
- JS Terminology
- JS Keywords

### Types in JS

- Types
- `Array.isArray()`
- Pass by Value vs Pass by Reference
- Type Coericion
- Static Typing in JS

### Closures and Prototypal Inheritance

- Functions are objects
- First-class citizens
- Higher-order functions
- Closures
- Closures & Memory
- Closures & Encapsulation
- Prototypal Inheritance

### Error Handling

- Handing Errors in JS
- Try Catch

### ES6 Features

- Spread Operator
- Destructuring
- Arrow Functions
- Default Parameters
- Classes
- Collections
- Modules (Pros and Cons & Common Modules)
- Promises
- Generators

### OOP (Object Oriented Programming)

- OOP Intro
- 4 Pillars of OOP
- Factory Functions
- `Object.create()`
- Constructor Functions
- `Object.create()` vs Class
- `this`
- Inheritance

### Data Structures

- What Are Data Structures?
- How Computers Store Data
- Data Structures in Differient Languages
- Operations on Data Structures
- Array Introduction
- Static vs Dynamic Arrays
- Implementing an Array
- Strings and Arrays
- Hash Tables
- Hash Functions
- Hash Collisions
- Hash Tables in Differient Languages
- `keys()`
- Hash Tables vs Arrays
- Hash Table Review
- Array Review

#### Data Structure Exercises

- Reverse a String
- Merge Sorted Arrays
- First Recurring Character
