---
sidebar_position: 4
---

# Calculate

## Sum

```js
const sum = [1, 2, 3, 4].reduce((acc, curr) => acc + curr, 0);
```

## Max

```js
const max = [5, 2, 8, 1].reduce((acc, curr) => Math.max(acc, curr), -Infinity);
```

## Average

```js
const numbers = [10, 20, 30, 40];
const average = numbers.reduce((acc, curr) => acc + curr, 0) / numbers.length;
```
