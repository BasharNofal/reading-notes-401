# Redux - Additional Topics

## Review, Research, and Discussion

1. By using react thunk
2. by exporting the new data to replace the state from the reducer. The action calling the reducer will be sent as a function rather than an object and then you can dispatch it.

### Terms

* **Middleware:** it's a middle point where extra functionality can be done. In react redux we use middleware to perform async operations.

* **Redux Thunk:** is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store’s dispatch method, which is then used to dispatch regular synchronous actions inside the function’s body once the asynchronous operations have been completed.

<hr>

## Preview

The **Redux Toolkit** package is intended to be the standard way to write Redux logic.