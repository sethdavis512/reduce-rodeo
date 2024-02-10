---
sidebar_position: 3
---

# How does reduce work?

Take an array and kicks its ass!

```js title="rodeo.js"
const rodeoAnimals = [
    { type: 'Cow', color: 'Brown' },
    { type: 'Bull', color: 'Black' },
    { type: 'Horse', color: 'White' }
];

const mappedAndFilteredAnimals = rodeoAnimals.reduce(
    (reducedAnimals, currentItem) => {
        return reducedAnimals;
    },
    []
);
```
