# Props and State

## Review, Research, and Discussion

1. No, it doesn't.

2. Iteration speed vs Realistic environment: Some tools offer a very quick feedback loop between making a change and seeing the result, but don’t model the browser behavior precisely. Other tools might use a real browser environment, but reduce the iteration speed and are flakier on a continuous integration server.

3. Converts the react app into HTML, JavaScript files so the browser can process them and run them, in other words make the react app readable for the browser.

4. React doesn't have a certain architecture that you have to follow. 

### Terms

**BDD:** refers to *Behavior-Driven Development*, it is a way for software teams to work that closes the gap between business people and technical people by encouraging collaboration across roles to build shared understanding of the problem to be solved.

**Acceptance Tests:** formal testing with respect to user needs, requirements, and business processes conducted to determine whether a system satisfies the acceptance criteria and to enable the user, customers or other authorized entity to determine whether to accept the system.

**Mounting:** Mounting is the phase in which our React component mounts on the DOM. This method is called just before a component mounts on the DOM or the render method is called. After this method, the component gets mounted.

**Build:** the process of converting the react app into HTML, JavaScript files so the browser can process them and run them, in other words make the react app readable for the browser.


<hr>

## Preview

**React SetState:**

* React components with state render UI based on that state. When the state of components changes, so does the component UI.

* `setState()` is the only legitimate way to update state after the initial state setup.

* Think of `setState()` as a request rather than an immediate command to update the component. For better perceived performance, React may delay it, and then update several components in a single pass. React does not guarantee that the state changes are applied immediately.

**React Forms:** just like in HTML, React uses forms to allow users to interact with the web page

**Handling Forms:**

* Handling forms is about how you handle the data when it changes value or gets submitted.

* In React, form data is usually handled by the components.

* When the data is handled by the components, all the data is stored in the component state

**React State:**

* React components has a built-in state object.

* The state object is where you store property values that belongs to the component.

* When the state object changes, the component re-renders.

**React Lifecycle:**

Each component in React has a lifecycle which you can monitor and manipulate during its three main phases.

The three phases are: Mounting, Updating, and Un-mounting.
to the DOM.

React has four built-in methods that gets called, in this order, when mounting a component:

constructor()
getDerivedStateFromProps()
render()
componentDidMount()
The render() method is required and will always be called, the others are optional and will be called if you define them.

**React Components:**

* Components are independent and reusable bits of code. They serve the same purpose as JavaScript functions, but work in isolation and return HTML via a render() function.

* Components come in two types, Class components and Function components, in this tutorial we will concentrate on Class components.

**React Props:**
React Props are like function arguments in JavaScript and attributes in HTML.