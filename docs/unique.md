---
sidebar_position: 9
---

# Unique

```js
const array = [1, 2, 3, 4, 2, 3, 5];
const uniqueValues = array.reduce(
    (acc, curr) => (acc.includes(curr) ? acc : acc.concat(curr)),
    []
);
```
