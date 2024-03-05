# Values and Variables

## Values

In the world of JavaScript, a value is like a piece of treasure, a nugget of information that can take various forms. Let's explore a few:

```javascript
let age = 25;           // 🌟 Number
let name = "John";      // 🌟 String
let isStudent = true;   // 🌟 Boolean
let person = {          // 🌟 Object
  firstName: "John",
  lastName: "Doe"
};
let greet = function() { // 🌟 Function
  console.log("Hello!");
};
```
# Variables

Think of variables as containers, holding these treasures. We declare them using the, `let`, `var`, or `const` keyword. Watch this:

```javascript
let x; // 📦 Declaration
x = 10; // 📦 Assignment
console.log(x); // 📦 Output: 10

let message = "Hello, World!";
console.log(message); // 📦 Output: Hello, World!
```

# Data Types and Basic Introduction of `let`, `var`, `const`

## Data Types

JavaScript, being the versatile language it is, juggles between different data types:

### Primitive Data Types:

- Number: Represents numeric values.
- String: Embraces textual data.
- Boolean: Chooses between true and false.
- Undefined: Represents the absence of a defined value.
- Null: Signals the absence of any value or object.

### Complex Data Types:

- Object: A magnificent collection of key-value pairs.
- Function: A masterful reusable block of code.

# `let`, `var`, `const`

- `var`: Once a hero, historically used, but it has function-level scope.

```javascript
var age = 30;

let: The modern champion, introduced in ES6, scoped to the nearest curly braces.
let age = 30;

const: The guardian of constants, introduced in ES6, value can not be re-assigned.
const pi = 3.14;
```

```javascript
// Using `let`
let age = 25;
age = 30; // 🔄 Valid re-assignment

// Using `const`
const pi = 3.14;
// pi = 3.14159; // ❌ Error: Assignment to a constant variable is not allowed

// Scoping example with `let`
if (true) {
  let localVar = "I am a local variable";
  console.log(localVar); // 🌐 Output: I am a local variable
}

// Scoping example with `var`
if (true) {
  var globalVar = "I am a global variable";
}
console.log(globalVar); // 🌐 Output: I am a global variable
```
