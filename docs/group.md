---
sidebar_position: 6
---

# Group

```js
const groupBy = (arr, objKey) =>
    arr.reduce((acc, cur) => ({ ...acc, [cur[objKey]]: cur }), {});
```
