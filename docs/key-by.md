---
sidebar_position: 6
---

# Key by

```js
const keyBy = (arr, objKey) =>
    arr.reduce((acc, cur) => ({ ...acc, [cur[objKey]]: cur }), {});
```
