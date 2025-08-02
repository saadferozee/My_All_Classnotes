

## *📘 JavaScript Beginner Notes (Up to Objects & Loops)*

---

*🌐 What is JavaScript?*
- JavaScript is a *high-level*, *interpreted*, and *dynamic* programming language.
- It is mainly used for *web development* to make websites interactive.
- Runs in the browser using a *JavaScript Engine* (e.g., Chrome uses *V8 Engine*).

---

*🖨️ Output in JavaScript*
```javascript
console.log("Hello, World!");
```
- `console.log()` is used to print output to the browser console.

---

*📦 Variables*

*Declaration Types:*
KeywordMutabilityScopeNotes`var`MutableFunctionOld way, avoid using`let`MutableBlockRecommended for changing values`const`ImmutableBlockRecommended for fixed values---

*🧮 Data Types*

*Primitive Types:*
- `String` → `"Hello"`
- `Number` → `42`
- `Boolean` → `true` / `false`
- `Undefined` → variable declared but not assigned
- `Null` → intentional absence of value
- `Symbol` → unique and immutable value

*Non-Primitive Types:*
- `Object` → `{ key: value}`
- `Array` → `[1, 2, 3]`
- `Function` → `function() {}`

---

*➕ Operators*

*Arithmetic:*
```javascript
+  -  *  /  %
```

*Assignment:*
```javascript
=  +=  -=  *=  /=
```

*Comparison:*
```javascript
==     // loose equality
===    // strict equality
!=     // loose inequality
!==    // strict inequality
<>  <=>=
```

*Logical:*
```javascript
&&   // AND
||   // OR
!    // NOT
```

*Ternary:*
```javascript
condition? valueIfTrue: valueIfFalse;
```

---

*🔀 Conditional Statements*

```javascript
if (condition) {
  // code
} else if (anotherCondition) {
  // code
} else {
  // code
}
```

---

*🔁 Loops*

*For Loop:*
```javascript
for (let i = 0; i < 5; i++) {
  console.log(i);
}
```

*While Loop:*
```javascript
let i = 0;
while (i < 5) {
  console.log(i);
  i++;
}
```

*Do...While Loop:*
```javascript
let i = 0;
do {
  console.log(i);
  i++;
} while (i < 5);
```

*For...of Loop (for arrays):*
```javascript
const fruits = ["apple", "banana", "mango"];
for (let fruit of fruits) {
  console.log(fruit);
}
```

*For...in Loop (for objects):*
```javascript
const person = { name: "John", age: 30};
for (let key in person) {
  console.log(key, person[key]);
}
```

---

*🧩 Functions*

*Function Declaration:*
```javascript
function greet(name) {
  return "Hello, " + name;
}
```

*Function Expression:*
```javascript
const greet = function(name) {
  return "Hello, " + name;
};
```

*Arrow Function:*
```javascript
const greet = (name) => "Hello, " + name;
```

---

*📚 Arrays*

*Declaration:*
```javascript
const numbers = [1, 2, 3, 4];
```

*Common Methods:*
- `push()` → add to end
- `pop()` → remove from end
- `shift()` → remove from start
- `unshift()` → add to start
- `length` → get array size
- `forEach()` → loop through array

---

*🧱 Objects*

*Declaration:*
```javascript
const person = {
  name: "Alice",
  age: 25,
  greet: function() {
    console.log("Hello!");
}
};
```

*Accessing Properties:*
```javascript
console.log(person.name);       // Dot notation
console.log(person["age"]);     // Bracket notation
```

*Adding/Modifying Properties:*
```javascript
person.city = "New York";
person.age = 26;
```

---

*🧠 Bonus: OOP Concepts in JS*

- *Encapsulation* → bundling data and methods
- *Inheritance* → one object inherits from another
- *Polymorphism* → same method behaves differently
- *Abstraction* → hiding complexity

---

Would you like me to turn this into a printable format or add examples for each section? I can also help you build small projects using these concepts!