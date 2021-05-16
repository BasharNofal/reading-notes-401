# Custom Hooks

## Review, Research, and Discussion

1. It refers to these three process: `mount` --> `update` --> `delete` with their functions.
2. `useCallback` will help in avoiding regeneration of functions when the functional component re-renders. However there isn't much of a performance difference caused by recreation of functions. You are specifying a function as a dependency to `useEffect` .
3. Because using `this` might be a bit confusing especially for whom is new to React, and they are more readable than class components.
4. Using hooks inside a loop.

### Terms

* **State hook:** `useState` which is equivalent to `this.setState`.
* **Effect hook:** `useEffect` which is equivalent to component lifecycle functions.
* **Reducer hook:** `useReducer` is usually preferable to `useState` when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. `useReducer` also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks. ([resource](https://reactjs.org/docs/hooks-reference.html))

<hr>

## Preview

**Custom Hooks** allow us to create our own hooks with additional functionality over the normal hooks in react.

`useReducer` is usually preferable to `useState` when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. `useReducer` also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.