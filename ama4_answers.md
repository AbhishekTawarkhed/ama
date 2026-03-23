###  Explain class and id
- **Class**: Used to apply styles or behaviors to multiple elements.  
  ```html
  <div class="container"></div>
  ```
- **Id**: Unique identifier for a single element.  
  ```html
  <div id="header"></div>
  ```

---

###  What is Web Browser API
- A **Web Browser API** provides built-in interfaces to interact with the browser.  
- Examples:  
  - **DOM API** → Manipulate HTML elements.  
  - **Fetch API** → Make network requests.  
  - **Storage API** → Store data in localStorage/sessionStorage.  

---

###  What are non-primitive datatypes
- Complex data types in JavaScript.  
- Examples:  
  - **Objects**  
  - **Arrays**  
  - **Functions**  
- They are mutable and can hold multiple values.

---

###  What are callback functions
- A **callback function** is passed as an argument to another function and executed later.  
  ```js
  function greet(name, callback) {
    console.log("Hello " + name);
    callback();
  }
  greet("John", () => console.log("Callback executed"));
  ```

---

###  Some object methods
- Common methods:  
  - `Object.keys(obj)` → Returns array of keys.  
  - `Object.values(obj)` → Returns array of values.  
  - `Object.entries(obj)` → Returns key-value pairs.  
  - `Object.assign(target, source)` → Copies properties.  
  - `Object.freeze(obj)` → Prevents modification.  

---

###  What is callback hell
- Occurs when multiple nested callbacks make code unreadable.  
  ```js
  doSomething(() => {
    doNext(() => {
      doAnother(() => {
        console.log("Too many nested callbacks!");
      });
    });
  });
  ```

---

###  What is spread operator
- Expands iterable values (arrays, objects).  
  ```js
  let arr = [1, 2, 3];
  let newArr = [...arr, 4, 5]; // [1,2,3,4,5]
  ```

---

###  What is hoisting
- JavaScript moves variable and function declarations to the top of their scope.  
  ```js
  console.log(a); // undefined
  var a = 10;
  ```

---

###  What is Object.seal method
- Prevents adding/removing properties but allows modification of existing ones.  
  ```js
  let obj = {name: "John"};
  Object.seal(obj);
  obj.age = 30; //  not allowed
  obj.name = "Doe"; // allowed
  ```

---

###  What is V8 engine
- Google’s open-source JavaScript engine.  
- Compiles JavaScript into machine code for fast execution.  
- Used in **Chrome** and **Node.js**.

---

###  What is push method in Array
- Adds one or more elements to the end of an array.  
  ```js
  let arr = [1, 2];
  arr.push(3); // [1,2,3]
  ```

---

###  Different ways to make Async in JavaScript
- **Callbacks** → Pass a function to be executed later.  
- **Promises** → Represent eventual completion/failure of async operation.  
- **Async/Await** → Write async code in synchronous style.  
- **Event Loop & Browser APIs** → `setTimeout`, `setInterval`, `fetch`, `addEventListener`.  
- **Generators with Promises** → Yield async flows with `function*`.  
- **Reactive Programming (RxJS)** → Streams and observables for async data.

---

###  What happens if we delete non-existence property
- Deleting a non-existent property has no effect and returns `true`.  
  ```js
  let obj = {a:1};
  delete obj.b; // true
  ```

---

###  Name some mutable methods
- **Mutable array methods**:  
  - `push()`  
  - `pop()`  
  - `shift()`  
  - `unshift()`  
  - `splice()`  
  - `sort()`  
  - `reverse()`

---

###  Difference between indexOf() and findIndex()
- **indexOf()** → Finds index of a specific value.  
  ```js
  [10, 20, 30].indexOf(20); // 1
  ```
- **findIndex()** → Finds index based on condition.  
  ```js
  [10, 20, 30].findIndex(x => x > 15); // 1
  ```

---

###  Difference between mutable and immutable
- **Mutable** → Can be changed after creation. No new memory space is required because the same reference is updated.  
  - Example: Arrays, Objects.  
  ```js
  let arr = [1, 2];
  arr.push(3); // modifies the same array
  ```

- **Immutable** → Cannot be changed once created. Any modification creates a new memory space (new reference).  
  - Example: Strings, Numbers, Booleans.  
  ```js
  let str = "Hello";
  str = str + " World"; // creates a new string, old one remains unchanged
  ```  

---  

