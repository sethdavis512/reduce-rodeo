---
sidebar_position: 8
---

# Reduce right

```js
const reduceReverse = (str) => {
    return str
        .split('')
        .reduceRight((sentence, letter) => (sentence += letter));
};
```
