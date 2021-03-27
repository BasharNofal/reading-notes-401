## Readings: Node Ecosystem, TDD, CI/CD

* `Array.map()` creates a new array by applying some changes to elements of another array, so for example I'd use if I wanted to multiply each element of an array by a number and store the results into a new array.

* `Array.reduce()` converts and array to one element, for example I'd use it if I wanted to find the summation of an array.

<hr>

* Using `.then()`:
```
superagent.get("url").then(result =>{
    console.log(result.body);
});
```

* Using `async` / `await`:
```
async function test (){
  let result = await superagent.get("url");
  console.log(result.body);
}
```
<hr>

* Promises are basically used when you want to use data in a callback function, but these data need some time to get fetched, so I'm basically telling the compiler to execute that callback function as soon as you receive the data.

<hr>

* Yes, callback functions are considered asynchronous, because when using them the code doesn't run in the normal flow.