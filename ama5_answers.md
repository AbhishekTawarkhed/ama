
### Types of Web Applications

- **Static Web Applications**  
  - Serve fixed content to the user.  
  - No interaction with databases or server-side logic.  
  - Built using HTML, CSS, and sometimes minimal JavaScript.  
  - Example: Portfolio websites, company info pages.  

- **Dynamic Web Applications**  
  - Content changes based on user interaction or server-side processing.  
  - Connected to databases and often use server-side languages (PHP, Python, Node.js).  
  - Can personalize content for each user.  
  - Example: Social media platforms, e-commerce sites.  

---


### What is a Decorator?
- A **decorator** is a design pattern in programming that allows behavior to be added to functions or classes without modifying their source code.
- In Python, decorators are functions that wrap another function to extend its behavior.
- Example:
```python
def decorator(func):
    def wrapper():
        print("Before function call")
        func()
        print("After function call")
    return wrapper

@decorator
def say_hello():
    print("Hello")
```

---

### Difference Between `querySelector` and `querySelectorAll`
- **`querySelector`**: Returns the **first** element that matches a CSS selector.
- **`querySelectorAll`**: Returns a **NodeList** of **all** elements matching the selector.
- Example:
```javascript
document.querySelector(".btn");      // First button
document.querySelectorAll(".btn");   // All buttons
```

---

### Django Components & Reusability
- Django promotes **reusability** through its modular design.
- Key components:
  - **Models**: Define database schema.
  - **Views**: Handle business logic.
  - **Templates**: Render HTML.
  - **Forms**: Manage user input.
  - **Apps**: Self-contained modules that can be reused across projects.
- Example: A `blog` app can be reused in multiple Django projects.

---

### Difference Between `onclick` and `addEventListener`
- **`onclick`**:
  - Assigns a single handler to an element.
  - Overwrites previous handlers.
- **`addEventListener`**:
  - Allows multiple handlers for the same event.
  - Provides more flexibility (options like `capture`, `once`).
- Example:
```javascript
element.onclick = () => console.log("Clicked once");
element.addEventListener("click", () => console.log("Clicked multiple"));
```

---

### What is a Frontend Framework?
- A **frontend framework** is a collection of tools and libraries that help build user interfaces efficiently.
- Examples:
  - **Angular**
  - **Vue.js**
  - **Svelte**

---

### What is a REST API?
- **REST (Representational State Transfer)** is an architectural style for designing networked applications.
- REST APIs use HTTP methods:
  - **GET**: Retrieve data
  - **POST**: Create data
  - **PUT/PATCH**: Update data
  - **DELETE**: Remove data
- Example: `GET /users/1` → fetch user with ID 1.

---

### What is HTTP?
- **HTTP (HyperText Transfer Protocol)** is the foundation of communication on the web.
- It defines how clients (browsers) and servers exchange requests and responses.
- Works on a request-response model:
  - Client sends request → Server responds with data.

---

### Common Web Application Architecture Patterns
- **Monolithic Architecture**: Single codebase handling all layers.
- **Microservices Architecture**: Independent services communicating via APIs.
- **Serverless Architecture**: Functions executed on demand in the cloud.
- **MVC (Model-View-Controller)**: Separation of concerns for maintainability.
- **Event-driven Architecture**: Components react to events asynchronously.

---
### Core HTTP Status Codes
- **100 Continue →** Informational: Request received, client should continue.
- **200 OK →** Success: Request successfully processed.
- **301 Moved Permanently →** Redirection: Resource has a new permanent URI.
- **404 Not Found →** Client Error: Requested resource not found.
- **500 Internal Server Error →** Server Error: Generic server-side issue.

---

### Difference Between Pre-Increment and Post-Increment
- **Pre-Increment (`++i`)**:
  - Increments the value first, then returns it.
- **Post-Increment (`i++`)**:
  - Returns the current value first, then increments.
- Example:
```c
int i = 5;
printf("%d", ++i); // Outputs 6
printf("%d", i++); // Outputs 6, then i becomes 7
```

---
