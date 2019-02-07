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

About the names: cant be a reserved keyword.  
List of reserved keyword:

abstract/arguments/await/const/continue/debugger/default/delete/do/double/else/enum/eval/export/extends/false/final/finally/float/for/function/goto/if/implements/import/in/instanceof/int/interface/let/long/native/new/null/package/private/protected/public/return/short/static/super/switch/synchronized/this/throw/throws/transient/true/try/typeof/var/void/volatile/while/with/yield

```javascript
let return = true
//Uncaught SyntaxError: Unexpected token return
```

## Primitive Types
