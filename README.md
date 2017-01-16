# Big O Assessment

---

What is the purpose of Big O?

> Answer here

---

What are 2 common things Big O describes?

> Answer here

---

What are the classes of Big O in order.

> Answer here

---

What does `O(n)` mean?

> Answer here

---

Write the worst-case time complexity of this function:

```js
function multiply (a, b) {
  return a * b
}
```

> Answer here

---

Write the worst-case time complexity of this function:

```js
function multiply (a, b) {
  var product = 0
  for (var n=a; a>0; a--) {
    product += b
  }
  return product
}
```

> Answer here

---

Write the worse-case time complexity of this function:

```js
function vectorMultiply (vA, vB) {
  var c = []
  for (var i=0; i<vA.length; i++) {
    var row = []
    for (var j=0; j<vB.length; j++) {
      row.push(vA[i] * vB[j])
    }
    c.push(row)
  }
  return c
}
```

> Answer here
