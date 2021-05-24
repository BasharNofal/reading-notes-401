# Redux - Asynchronous Actions

## Review, Research, and Discussion

1. It really depends on the application itself, but assuming that for each change the same action or functionality will be triggered so it should be less grainy, for example when triggering an action based on a change of form data.
2. Again it depends on the application, but for larger projects which has complex actions this might be a con because it might result in performance issues.
3. Having more grainy actions.

### Terms

* **Store:** it's where state object is stored.
* **Combined Reducers:** helper function that combines multiple reducers into one reducer.

<hr>

## Preview

Normally redux doesn't know about async operations, it only dispatch an action, call reducer function which changes the state that will reflect on the UI. Any async operation need a middleware to be done which will delay the dispatching the action.

**Redux Thunk** is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store’s dispatch method, which is then used to dispatch regular synchronous actions inside the function’s body once the asynchronous operations have been completed.


