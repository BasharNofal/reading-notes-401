# Hooks API

## Review, Research, and Discussion

1. Because using react routing libraries we can render different components depending on the url entered.

2. Inside the `<BrowserRouter />`, outside a `<Route />`, because we need to wrap the whole application with `<BrowserRouter />`, and outside `<Route />` because we only use `<Route />` inside of `<Switch />` to let the app decide which component to render based on the url.

3. `Props.children` is a special prop, automatically passed to every component that can be used to render the content included between the opening and closing tags when invoking a component. Content passed through `props.children` can include `undefined`, `null`, boolean, a number, a string, a React element or an array of any of these recursively, it can also be a function returning one of these types.

### Terms

**Composition:** is a development pattern based on React's original component model where we build components from other components using explicit defined props or the implicit children prop.

**Children / Child Components:** components that are placed or defined inside of other components.

**SERVER SIDE:** HashRouter uses a hash symbol in the URL, which has the effect of all subsequent URL path content being ignored in the server request (ie you send "www.mywebsite.com/#/person/john" the server gets "www.mywebsite.com". As a result the server will return the pre # URL response, and then the post # path will be handled by parsed by your client side react application.[resource](https://stackoverflow.com/questions/51974369/what-is-the-difference-between-hashrouter-and-browserrouter-in-react)

**CLIENT SIDE:** BrowserRouter will not append the # symbol to your URL, however will create issues when you try to link to a page or reload a page. If the explicit route exists in your client react app, but not on your server, reloading and linking(anything that hits the server directly) will return 404 not found errors.[resource](https://stackoverflow.com/questions/51974369/what-is-the-difference-between-hashrouter-and-browserrouter-in-react)

<hr>

## Preview

**Hooks:** hooks are functions that let you “hook into” React state and lifecycle features from function components. Hooks don’t work inside classes — they let you use React without classes. 

Hooks let you always use functions instead of having to constantly switch between functions, classes, higher-order components, and render props.