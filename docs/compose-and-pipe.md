---
sidebar_position: 6
---

# Compose & pipe

## Compose

```js
const compose =
    (...functions) =>
    (input) =>
        functions.reduceRight((acc, fn) => fn(acc), input);
```

## Pipe

```js
const pipe =
    (...functions) =>
    (input) =>
        functions.reduce((acc, fn) => fn(acc), input);
```
