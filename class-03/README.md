# Express REST API

### Review, Research, and Discussion


1. * Add the time of the request to the response.
   * Error handling.
   * Checking the value of a certain parameter in the request.

2. False.
3. By using `next()`, if it was empty it will continue to the next function, else it should point to a route.
4. When the user hits the route, but before the response. 
5. When writing more than `resonse()` statements for a single http request.

<hr>

### Terms

* **Middleware:** A function that checks the incoming requests and prepares it for a custom process, and upon the results of that process the response will be sent.
* **Request Object:** It's a parameter that express adds to the http request, it contains info such as, method type, IP address, and other parameters.
* **Response Object:** It's a parameter express adds which allows to send a response for a http request.
* **Application Middleware:** Binding a middleware to the app object.
* **Routing Middleware:** Middleware that works after a route gets hit by the user.
* **Test Driven Development:** A practice in which we write a test for the expected outputs of different inputs for our code and then we write a code that passes that test.
* **Behavioral Testing:** it's used for getting different types of Errors such as function missing, performance, initializing and terminating errors etc. It takes inputs from the user and shows outputs directly.
