# JS-CheatSheet 🚀

A Javascript CheatSheet to have in mind bro

---

## Development Enviorment

- Browser
  - Chrome --> V8 🔥
  - Safari --> SpiderMonkey 💘
  - Safari --> WebKit
  - Explorer --> Chakra 💩
- Node
  - (The V8 in C++) 💽

---

## Separation of concerns

- CSS

```javascript
<link rel="stylesheet" href="style.css">
```

- JS

```javascript
<script src="" />
```

---

## Variables

- VAR

```javascript
var average = 5;
var average = (average + 1) / 2;
//> average
//> 3;
```

- LET

```javascript
let value = ‘hello world’
let value = ‘what is new’
// -> throws TypeError: Identifier 'value' has already been declared
```

- CONST

```javascript
const c = true;
c = false;
//> c
//> true;
```

About the names:

- Cant be a reserved keyword.  
  List of reserved keyword:

abstract/arguments/await/const/continue/debugger/default/delete/do/double/else/enum/eval/export/extends/false/final/finally/float/for/function/goto/if/implements/import/in/instanceof/int/interface/let/long/native/new/null/package/private/protected/public/return/short/static/super/switch/synchronized/this/throw/throws/transient/true/try/typeof/var/void/volatile/while/with/yield

```javascript
let return = true
//Uncaught SyntaxError: Unexpected token return
```

- Variable names should be meaningful
- Can not start with a number
- can not contain spaces or hyphen (use camel notation)
- names are case-sensitive

## Primitive Types

- String

```javascript
let name = "seba";
```

- Number

```javascript
let age = 44;
```

- Boolean

```javascript
let isChecked = false;
```

- Undefined

```javascript
let firstName; //undefined
```

- null

```javascript
let secoundName = null;
```

## Reference Types

- Object

```javascript
let person = {
    name: 'Seba',
    mentalAge: 13,
    hadBeenThere: false
}
//to change the object:
// 1. Dot Notation
person.name:'Juan'
// 2. Bracket Notation
let selection = 'name'
person[selection] = 'AfroLacio'//to acces in a dinamic way

```

- Arrays

```javascript
let selectedColors = ["red", "blue"];
selectedClors[2] = "green";
//>typeof selectedColors
//>object
//Arrays are Objects and objects have properties, ex:
//>console.log(selectedColors.length)
//>3
```

- Functions

```javascript
//Function that perform a task
function greet(name) {
  //name is a parameter
  alert("hi " + name);
}
greet("seba"); //in this case Seba is an argument
```

```javascript
//Function that calculate a value:
function square(number) {
  return (number = number * number);
}
console.log(square(2));
//>4
console.log(square(3));
//>9
```

## Operators

- Arithmetic operators

```javascript
let x = 10;
let y = 3;

let q = x + y; //Addition
let w = x - y; //Subtraction
let e = x * y; //Multiplication
let r = x / y; //Division
let t = x % y; //Modulus (division remainder)
let y = x++; //Increment
let i = x--; //decrement
let u = x ** y; //exponentiation
```

- Assigment operators

```javascript
let x = 10 //equal operator
let x += 5 // adition assigment operator
let x *= 3 //multiplication asigment
```

- Comparison Operators

```javascript
console.log(x > 1); //will return a boolean, true or false
console.log(x === 1); //is strict equal? (same type and value)
console.log(x == 1); //is lose equal?(same value)
console.log(x !== 1); //is not equal?
```

- Ternary Operator

```javascript
let points = 150;
let type = points > 100 ? "gold" : "silver";
//ternary operator allow to asign diferente values to variables
```

- Logical operators

```javascript
//logical AND &&
console.log(true && true); //true
console.log(true && false); //false

//logical OR ||
console.log(true || false); // true
console.log(false || false); //false

//logical NOT !
//convert to opposite

//logical with non booleans
console.log(true || "seba"); //seba

//falsy:
//undifined
//null
//0
//false
//''
//NaN
// Anything that is not falsy is trusy
```

- Logical Operators with Non-booleans

para mas adelante

```

---

## Arrays

How to convert a nodeList to an Array
con el spread operator
[...nodeList]
```
