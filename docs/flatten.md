---
sidebar_position: 4
---

# Flatten

```js
const flattened = [
    [1, 2],
    [3, 4],
    [5, 6]
].reduce((acc, curr) => acc.concat(curr), []);
```
