# Authentication

## Review, Research, and Discussion

1. **Singleton:** is design pattern where we limit the initiation of instance of a constructor to only one and unique instance.

2. In the following example if we want to create an instance we would need to invoke the method `getProcessManager()` then it will check if `pManager` which is an instance was created before then it will return the same instance which is `pManager`, if not it will initiate a new instance. Similarly using classes.

 ```
const Singleton = (function(){
  let pManager

  function ProcessManager() { /*...*/ }

  function createProcessManager()
  {
    pManager = new ProcessManager()
    return pManager
  }

  return {
      getProcessManager: () =>
      {
        if(!pManager)
          pManager = createProcessManager()
        return pManager
      }
  }
})()

const singleton = Singleton.getProcessManager()
const singleton2 = Singleton.getProcessManager()

console.log(singleton === singleton2)
``` 
[Resource](https://github.com/pkellz/devsage/blob/master/DesignPatterns/SingletonPattern.js)

3. Singleton, because I wouldn't change it or get different result every time it's being used, as an example JQuery.

<hr>

### Terms

**Router Middleware:** Middleware that operates between the request and the response.

**Dynamic Module Loading:** Importing module at runtime only when it's needed by using the command `module.import()`.

**Singleton Pattern:** Is design pattern where we limit the initiation of instance of a constructor to only one and unique instance.

**CRUD:** REST api operations (create: POST, read: GET, update: PUT, delete: DELETE).

**Mock Testing:** Tests that simulate the behavior of production stage.

<hr>

## Preview

Passwords are stored in database encrypted using different algorithms, but the problem is that these passwords can be reversed using the same algorithms such as *MD5*, *SHA1*, *SHA256*, *SHA512*, *SHA-3*. The solution to this is using an adaptive algorithm such as *Bcrypt* which uses key stretching technique which basically making weak passwords much more longer and stronger, bcrypt also have a factor that you can determine which ads more randomness to the encryption process.