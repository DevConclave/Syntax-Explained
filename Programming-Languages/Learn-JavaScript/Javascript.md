# Learn JavaScript Basics

Welcome to the beginner's guide to learning JavaScript! In this guide, we'll cover the fundamental concepts that form the building blocks of the JavaScript programming language.

## Table of Contents

- [Variables](#variables)
- [Data Types](#data-types)
- [Operators](#operators)
- [Equality, Logic, and Control Flow](#equality-logic-and-control-flow)
- [Functions](#functions)
- [Input and Output](#input-and-output)
- [Comments](#comments)
- [Conclusion](#conclusion)

<br>

## Variables

### Variable Types: `var`, `let`, `const`

In JavaScript, variables are used to store data. There are three ways to declare variables: `var`, `let`, and `const`.

```javascript
// Using var
var name = "John";

// Using let
let age = 25;

// Using const
const pi = 3.14159;
```

#### Rules for Naming Variables:

1. The name should be unique.
2. Avoid using reserved keywords of JavaScript.
3. The name must start with a letter, underscore (`_`), or dollar sign (`$`).

<br>

## Data Types

### Primitive Data Types:

- Strings: `"Hello, World!"`
- Numbers: `5`, `3.14`, `-7`
- Boolean: `true`, `false`
- Null: `null`
- Undefined: `undefined`
- Symbol: *(rarely used)*

```javascript
let count = 10;
let isLogged = true;
let value = null;
let person;
```

### Complex Data Types:

- Object: Forms the foundation for JavaScript programming.

```javascript
// Creating an object
const person = {
    name: "Alice",
    age: 30
};
```
<br>

## Operators

JavaScript includes various operators for performing operations on values.

### Arithmetic Operators:

```javascript
let num1 = 10;
let num2 = 3;

let sum = num1 + num2;
let difference = num1 - num2;
let product = num1 * num2;
let quotient = num1 / num2;
let remainder = num1 % num2;
```

### Assignment Operators:

```javascript
let x = 5;
x += 3; // equivalent to x = x + 3
```

### Comparison Operators:

```javascript
let a = 10;
let b = 15;

console.log(a == b); // Output: false
console.log(a > b); // Output: false
console.log(a <= b); // Output: true
```

### Logical Operators:

```javascript
let p = true;
let q = false;

console.log(p && q); // Output: false
console.log(p || q); // Output: true
console.log(!p); // Output: false
```

### Increment/Decrement Operators:

```javascript
let count = 5;
count++; // count is now 6
count--; // count is now 5
```

<br>

## Equality, Logic, and Control Flow

### Conditional Statements:

- `if` Statement
- `else if` Statement
- `switch` Statement

```javascript
let time = 14;

if (time < 12) {
    console.log("Good morning!");
} 
else if (time < 18) {
    console.log("Good afternoon!");
} 
else {
    console.log("Good evening!");
}
```

### Loops:

- `for` Loop
- `while` Loop

```javascript
for (let i = 0; i < 5; i++) {
    console.log("Iteration: " + i);
}

let count = 0;
while (count < 5) {
    console.log("Count: " + count);
    count++;
}
```

<br>

## Functions

Functions are reusable blocks of code.

```javascript
function greet(name) {
    console.log("Hello, " + name + "!");
}

greet("Alice"); // Output: Hello, Alice!
```

<br>

## Input and Output

- Output: `console.log("Hello, world!");`
- Input: `prompt("Enter your name:");`

<br>

## Comments

You can use comments to explain your code.

```javascript
// This is a single-line comment

/*
This is a multi-line comment.
It can span multiple lines.
*/

// You can also use comments to disable code temporarily
// console.log("This won't be printed");
```

## Conclusion

Congratulations! You've learned the basics of JavaScript, from variables and data types to operators, logic, functions, input/output, and comments. 
This foundation will empower you to start writing simple programs and pave the way for exploring more advanced topics. 
Remember, programming is a continuous journey, so keep practicing and experimenting. Happy coding!
