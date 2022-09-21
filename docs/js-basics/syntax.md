---
sidebar_position: 1
---

# JS Syntax

Javascrip is case sensitive:

```js
let NUMBER = 1;
let Number = 2;
let number = 3;

console.log(NUMBER); // 1
console.log(Number); // 2
console.log(number); // 3
```

Naming identifires
Variables, functions 
Rules the identifier must start with a letter, _ or $

```js
let name = "johm";
let _age = 20;
let $location = "New york";

// invalid identifier
let 123 = "johm";
let %age = 20;
let 1name = "New york";
// valid identifier (letters, number, $ and _ )
let name1 = "johm";
let last_name = "New york";
let $fistName = "johm";
```

Convension identifier
Camel case (lastName, firstName)

```js
let firstName = "juan";
let lasName = "Gonzo";
```

Semicolons  - Not mandatory

```js
let city = "Bogota";
let country = "Colombia"
```