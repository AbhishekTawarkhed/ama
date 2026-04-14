
**Difference between `null` and `undefined` in JavaScript**  
- `undefined` means a variable has been declared but not assigned a value. It’s the default state.  
- `null` is an intentional assignment by the developer to represent “no value” or “empty.”  
- Example:  
  ```js
  let a;        // a is undefined
  let b = null; // b is explicitly set to null
  ```
---
**What is context in JavaScript**  
- Context refers to the value of `this` inside a function.  
- It depends on how the function is invoked:  
  - As a method → `this` refers to the object.  
  - As a standalone function → `this` refers to the global object (or `undefined` in strict mode).  
- Context is different from scope: scope is about variable access, context is about the object binding.
---
**Running Django server on a different port**  
- By default, Django runs on port 8000.  
- You can specify another port when starting the server:  
  ```bash
  python manage.py runserver 8080
  ```
- This runs the server on `http://127.0.0.1:8080`.
---
**Open/Close Principle (OCP)**  
- A class/module should be open for extension but closed for modification.  
- Meaning: you should be able to add new functionality without changing existing code.  
- Example: Instead of editing a class directly, you extend it or use interfaces. This reduces bugs and keeps tested code stable.
---
**Async and Await in JavaScript**  
- `async` declares a function that returns a Promise.  
- `await` pauses execution until the Promise resolves, making asynchronous code look synchronous.  
- Example:  
  ```js
  async function fetchData() {
    let response = await fetch('/api/data');
    let data = await response.json();
    console.log(data);
  }
  ```
---
**Difference between `makemigrations` and `migrate` in Django**  
- `makemigrations`: Detects changes in models and creates migration files.  
- `migrate`: Applies those migration files to the database, updating schema.  
- Together, they keep your database structure in sync with your models.
---
**What is CSRF**  
- Cross-Site Request Forgery is a security attack where a malicious site tricks a user into submitting requests to another site where they are authenticated.  
- Django protects against CSRF by requiring a CSRF token in POST forms.
---
**What is Django REST Framework (DRF)**  
- A toolkit for building Web APIs with Django.  
- Provides serializers, viewsets, routers, authentication, and permissions.  
- Makes it easier to expose Django models and logic as RESTful endpoints.
-------
**Opening Django Shell**  
- Run:  
  ```bash
  python manage.py shell
  ```  
- Opens an interactive Python shell with Django environment loaded, letting you test queries and logic.
---
**What is Django Admin Panel**  
- A built-in interface for managing models and data.  
- Accessible at `/admin` after creating a superuser.  
- Lets you add, edit, and delete records without writing SQL.
---
**What is MVT in Django**  
- Model–View–Template architecture.  
- Model: Handles data and database.  
- View: Contains business logic and interacts with models.  
- Template: Handles presentation (HTML).  
- Django uses MVT instead of MVC, with templates replacing controllers.
---
**Workflow of Django**  
1. User sends a request via URL.  
2. URL dispatcher maps it to a view.  
3. View interacts with models if needed.  
4. View passes data to a template.  
5. Template renders HTML and sends response back to the user.
---
**Features of JavaScript**  
- Lightweight, interpreted language.  
- Supports event-driven, functional, and object-oriented programming.  
- Runs in browsers and servers (Node.js).  
- Dynamic typing, first-class functions, and asynchronous programming support.
---
**What is ORM in Django**  
- Object-Relational Mapping layer.  
- Lets you interact with the database using Python classes instead of SQL.  
- Example:  
  ```python
  User.objects.filter(is_active=True)
  ```
  translates to SQL queries automatically.
---
**Defining Primary Key in Django**  
- By default, Django adds an `id` field as the primary key.  
- You can define your own:  
  ```python
  class Student(models.Model):
      roll_number = models.IntegerField(primary_key=True)
      name = models.CharField(max_length=100)
  ```
---
