# Learn C++ Basics

Welcome to the beginner's guide to learning C++! In this guide, we'll cover the fundamental concepts that form the foundation of the C++ programming language.

## Table of Contents

- [Introduction](#introduction)
- [Variables](#variables)
- [Data Types](#data-types)
- [Operators](#operators)
- [Conditional Statements](#conditional-statements)
- [Loops](#loops)
- [Functions](#functions)
- [Input and Output](#input-and-output)
- [Comments](#comments)
- [Conclusion](#conclusion)

<br>

## Introduction

C++ is a versatile programming language known for its power and performance. It allows you to write efficient and high-performance code while providing a wide range of features for various applications.

## Variables

### Variable Types: `int`, `float`, `double`

In C++, variables are used to store data. Common variable types are:

```cpp
int age = 25;
float temperature = 98.6;
double pi = 3.14159;
```

<br>

## Rules for Naming Variables:
1. Variable names can contain letters, digits, and underscores.
2. Variable names must start with a letter or underscore.
3. C++ is case-sensitive, so myVar and myvar are considered different.

<br>

## Data Types

### Primitive Data Types:

***int:*** Integer values

***float:*** Single-precision floating-point values

***double:*** Double-precision floating-point values

***char:*** Single characters

***bool:*** Boolean values

```cpp
int count = 10;
float price = 5.99;
char grade = 'A';
bool isLogged = true;
```

### Complex Data Types:

***Arrays:*** Collections of elements of the same data type

***Strings:*** Sequences of characters

***Structures:*** User-defined data types

***Pointers:*** Memory addresses of variables

```cpp
int numbers[] = {1, 2, 3, 4, 5};
std::string name = "John";
struct Person { std::string name; int age; };
Person person = {"Alice", 30};
int* ptr = &count;
```

<br>

## Operators
C++ provides various operators for performing operations on values.

### Arithmetic Operators:

```cpp
int num1 = 10;
int num2 = 3;

int sum = num1 + num2;
int difference = num1 - num2;
int product = num1 * num2;
int quotient = num1 / num2;
int remainder = num1 % num2;
```

### Assignment Operators:

```cpp
int x = 5;
x += 3; // equivalent to x = x + 3;
```

### Comparison Operators:

```cpp
int a = 10;
int b = 15;

std::cout << (a == b) << std::endl; // Output: 0 (false)
std::cout << (a > b) << std::endl; // Output: 0 (false)
std::cout << (a <= b) << std::endl; // Output: 1 (true)
```

### Logical Operators:

```cpp
bool p = true;
bool q = false;

std::cout << (p && q) << std::endl; // Output: 0 (false)
std::cout << (p || q) << std::endl; // Output: 1 (true)
std::cout << (!p) << std::endl; // Output: 0 (false)
```

<br>

## Conditional Statements

### if Statement:
```cpp
int age = 18;

if (age >= 18) {
    std::cout << "You are an adult." << std::endl;
}
else {
    std::cout << "You are a minor." << std::endl;
}
```

### else if Statement:

```cpp
int time = 14;

if (time < 12) {
    std::cout << "Good morning!" << std::endl;
}
else if (time < 18) {
    std::cout << "Good afternoon!" << std::endl;
}
else {
    std::cout << "Good evening!" << std::endl;
}
```

<br>

## Loops

### for Loop:

```cpp
for (int i = 0; i < 5; i++) {
    std::cout << "Iteration: " << i << std::endl;
}
```

### while Loop:

```cpp
int count = 0;

while (count < 5) {
    std::cout << "Count: " << count << std::endl;
    count++;
}
```

<br>

## Functions
Functions allow you to organize and reuse code.

```cpp
void greet(std::string name) {
    std::cout << "Hello, " << name << "!" << std::endl;
}

greet("Alice"); // Output: Hello, Alice!
```
<br>

## Input and Output

```
Output: std::cout << "Hello, world!" << std::endl;
Input: std::cin >> userInput;
```

<br>

## Comments
Use comments to explain your code.

```cpp
// This is a single-line comment

/*
This is a multi-line comment.
It can span multiple lines.
*/

// You can also use comments to temporarily disable code
// std::cout << "This won't be printed" << std::endl;
```

<br>

## Conclusion
Congratulations! You've learned the basics of C++, including variables, data types, operators, conditional statements, loops, functions, input/output, and comments.
This foundational knowledge will enable you to write simple programs and set the stage for exploring more advanced C++ concepts.
Remember, practice is essential for mastering programming. Happy coding!
