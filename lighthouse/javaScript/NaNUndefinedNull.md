## Null, Undefined, and NaN

---

**null** refers to the "value of nothing", while **undefined** refers to the "absence of value".

![](image/NaN.PNG)

## Implicit type coercion

---

JavaScript is known as a loosely typed language.

Basically, this means that when you’re writing JavaScript code, you do **not need to specify data types**. Instead, when your code is interpreted by the JavaScript engine it will automatically be converted into the "appropriate" data type. This is called implicit type coercion.

## Comparison Operators

---

== and != are loose operators (bad practice)!!!

### Strict Equality

```
=== and !==
Above are strict equality and strict inequality operators
```

Examples:

```
"1" === 1 //Returns: false

This returns false because the string "1" is not the same type and value as the number 1.
```

```
0 === false //Returns: false

This returns false because the number 0 is not the same type and value as the boolean false.
```

```
0 !== true //Returns: true

and

'1' !== 1 //Returns: true
```
