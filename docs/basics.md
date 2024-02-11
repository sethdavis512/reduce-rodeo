---
sidebar_position: 3
---

# Basics

A method on an array.

The MDN definition:

> The reduce() method of Array instances executes a user-supplied "reducer" callback function on each element of the array, in order, passing in the return value from the calculation on the preceding element. The final result of running the reducer across all elements of the array is a single value.

[Read more](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)

## Parameters

Reduce takes two parameters:

-   `Callback function` - A function that gets called for each item in the array
-   `Initial value` - array, object, number, boolean

## Example

```js title="rodeo.js"
const rodeoAnimals = [
    { type: 'Cow', color: 'Brown' },
    { type: 'Bull', color: 'Black' },
    { type: 'Horse', color: 'White' }
];
const initialValue = [];

const mappedAndFilteredAnimals = rodeoAnimals.reduce(
    (reducedAnimals, currentAnimal) => {
        if (currentAnimal.color !== 'Brown') {
            reducedAnimals.push({
                ...currentAnimal,
                brand: 'W'
            });
        }

        return reducedAnimals;
    },
    initialValue
);
```
