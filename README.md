# core-code-from-scratch-04-01

## ---Functions---
[How do functions work?](https://www.jshero.net/en/koans/function.html)

* Solution / /
``` javascript
function hello() {
  return 'Hello world!';
}
```

---

## ---Multiple functions---
[Making 2 or more functions](https://www.jshero.net/en/koans/function2.html)

* Solution / /
``` javascript
function a() {
  return 'Hello a!';
}

function b() {
  return 'Hello b!';
}
```

---
## ---Function call---
[How do call a function?](https://www.jshero.net/en/koans/functioncall.html)

* Solution / /
``` javascript
function greet() {
  return 'Haydo!';
}

let salutation = greet();
```

---
## ---What is x (exercise)---

* Which value does x have after execution of the following code?
``` javascript
function hello() {
  return 'Hi!';
}

let x = hello();
```

* Solution / /
``` javascript
'Hi!'
```

---
## --- Funtion with parameter---

[Defining the parameter of a function to be used in future references](https://www.jshero.net/en/koans/parameter.html)

* Solution / /
``` javascript
function echo(varbl){
  return varbl
}
```
