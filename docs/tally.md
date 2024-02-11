---
sidebar_position: 8
---

# Tally

```js
const wordCount = ['apple', 'banana', 'apple', 'orange'].reduce((acc, curr) => {
    acc[curr] = (acc[curr] || 0) + 1;
    return acc;
}, {});
```
