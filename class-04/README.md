# Data Modeling

## Review, Research, and Discussion

1. * TDD ensures that the code  meets the desired requirements.
    * Predicting what inputs might the user enters before start coding will result in having higher quality code.
    * Save project cost in the long run.

2. To run functions before or after the test.

3. Running tests only some parts of the code might give an output different than what will the actual output going to be.

4. Classes aren't hoisted whereas constructors are, also using classes will save memory in case of not calling a method when using classes because it won't be saved in that object if it wasn't invoked unlike constructor prototype.

5. REST are simple because you don't need to worry about how to format your data, also they are easily modified, lastly they are fast because they support caching.

<hr>

## Terms

* **Functional Programming:** Basically, it means avoiding shared data between functions and making my code easily modular, which results in having readable, and free of bugs code, but that doesn't mean that it will be shorter.

* **Object-Oriented Programming:** Structuring the code in a way that it would be reusable, simple and utilizes classes/constructor.

* **Classes:** It's a new way of declaring constructors/blueprints that was introduced in ES6.

* `super`: It's used for calling the constructor of the parent class which can be used if you want to use a property that exists in the parent class.

* `this`: Points at the parent object that it was called inside except for arrow functions.

* **Test Driven Development:** Applying tests before writing the code, then writing a code that will pass the test.

* **jest:** Node framework for applying tests.

* **Continuous Integration:** When working on multiple branches on github the branches' versions of the code will become different more and more so eventually this will cause problems when merging or maybe some deletions will occur by mistake, so CI will run tests with each pull request which will make sure that branches' versions are compatible with main branch.

**REST:** It's a standard architectural style API used by what's called RESTful services, what REST does is communicating or send http requests from websites to servers to do one of four operations: Create, Read, Update, and Delete (CRUD).

**Data Model:** A diagram that explains the relations between each data element in a project.

<hr>

## Preview

**SQL vs NoSQL:** **SQL** uses tables and schemas, whereas **noSQL** uses something similar to trees and json objects. **SQL** uses relations between the tables, whereas **noSQL** don't. **NoSQL** can store more data more easily than **SQL**.
**NoSQL** have multiple repeated data. **NoSQL** is faster than **SQL**. 
