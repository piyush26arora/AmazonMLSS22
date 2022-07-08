# Javascript (Made by Brenden Eich)
(Client Side Language)

-> for browser and not servers

->NodeJS - (Server Side) 

-> applications / web apps

<hr>

## JS Engine Working
### Interpreter(code to bytecode) 

|

|

|

### Compiler / JIT(just in time) 

{ bytecode to machine code and also execute/implement it when it is reading}


```
NOTE: Chrome's V8 JS Engine has Compiler named TURBO FAN / SEA OF NODES

Interpreter named IGNITION 
```
|

|

|

### Machine code


<hr>


```
// AOT - Ahead Of Time (Angular)

Why would you use AOT compilation?

The Angular ahead-of-time (AOT) compiler converts your Angular HTML and TypeScript code into efficient JavaScript code during the build phase before the browser downloads and runs that code. ... The browser loads executable code so it can render the application immediately, without waiting to compile the application first.

_______

What is difference between AOT and JIT?

JIT downloads the compiler and compiles code exactly before Displaying in the browser. AOT has already complied with the code while building your application, so it doesn't have to compile at runtime. ... Loading in AOT is much quicker than the JIT because it already has compiled your code at build time.
```

<hr>

## JS
* Dynamic
```
Types of variables are judged at runtime.

Most of the stuff is function-oriented and thus dynamic.
```
* Weakly typed
```
Variables are not bound to a specific type. It judges on its own (if it's an int, char, float, string etc)

JS + C++ => TypeScript (to overcome problems rising from this)
e.g.: var a:number = 10 ;
```
* Compiled at Runtime

<hr>

```
* JavaScript is not Object-Oriented, it is Function Oriented

* Flutter is weakly + strongly typed language.
```

## JS Engines in different Browsers
* Chrome -> V8 (fastest)
* Mozilla -> Spider Monkey
* IE -> Chakra
* Safari -> JavaScriptCore

<hr>

## Data types in JS
``` 
- undefined
- Not defined ============> Reference Error
- Number
- String
- Object
- Array
- NaN (Not a Number)
- Infinity
- NULL
```
<hr>

```javascript

// declaration
var a = 10 ;
let b = 20 ;
const c = 3;

// var naming - start number NOT allowed, underscore(_) in start allowed, camelCase is allowed, dollarSign($) also allowed(not allowed in other languages)

/*
Expressions 
+, -, *, /, %, ||, &&, ==, !=, ++, --, +=, -=, *=, /=, ===, !==
*/

// == checks value by typecasting
// === checks type of data, then value
```
