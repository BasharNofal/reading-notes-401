# Context API

## Review, Research, and Discussion

1.
   * `useMemo()` will only recompute the memoized value when one of the dependencies has changed. This optimization helps to avoid expensive calculations on every render. It's usually used to optimize performance.
   * `useReducer()` is usually preferable to `useState` when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. `useReducer` also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

2. In order for us to be able to distinguish them from normal functions.
3. Allows us to create our own hooks with additional functionality over the normal hooks in react.
4. `useToggle`.

### Terms

* **Reducer:** function that determines changes to an application’s state. It uses the action it receives to determine this change.

<hr>

## Preview

**Context** provides a way to share data between components without having to explicitly pass a prop through every level of the tree, which is very useful when dealing with deeply nested components.
