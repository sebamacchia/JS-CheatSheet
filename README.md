# JS-CheatSheet 🚀

A Javascript CheatSheet to have in mind bro

## Development Enviorment

- Browser
  - Chrome --> V8 🔥
  - Safari --> SpiderMonkey 💘
  - Safari --> WebKit
  - Explorer --> Chakra 💩
- Node
  - (The V8 in C++) 💽

## Separation of concerns

- CSS

```javascript
<link rel="stylesheet" href="style.css">
```

- JS

```javascript
<script src="" />
```

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
    hadBenThere: false
}
//to change the object:
// 1.Dot Notation
person.name:'Juan'
// 2. Bracket Notation
let selection = 'name'
person[selection] = 'AfroLacio'//to acces in a dinamic way

```

- Arrays

```javascript
let name = "seba";
```

- Functions

```javascript
let name = "seba";
```
