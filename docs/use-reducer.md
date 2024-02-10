---
sidebar_position: 6
---

# useReducer

```js
const [state, dispatch] = useReducer(reducer, initialArg, init?)
```

```js
import { useReducer } from 'react';

function reducer(state, action) {
    if (action.type === 'incremented_age') {
        return {
            age: state.age + 1
        };
    }
    throw Error('Unknown action.');
}

export default function Counter() {
    const [state, dispatch] = useReducer(reducer, { age: 42 });

    return (
        <>
            <button
                onClick={() => {
                    dispatch({ type: 'incremented_age' });
                }}
            >
                Increment age
            </button>
            <p>Hello! You are {state.age}.</p>
        </>
    );
}
```
