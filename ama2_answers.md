## What is CSS?
CSS (Cascading Style Sheets) is a stylesheet language used to describe the presentation of HTML documents. It controls layout, colors, fonts, spacing, and overall design, separating content from design.

---

## CSS Selectors
CSS selectors are patterns used to target and style HTML elements.  
Examples:
- `element` → targets all `<p>` or `<div>` tags.
- `.class` → targets elements with a specific class.
- `#id` → targets an element with a unique ID.
- `element.class` → targets a specific element with a class.

---

## A in ACID in SQL
ACID stands for Atomicity, Consistency, Isolation, Durability.  
- **A → Atomicity**: Ensures that a transaction is all-or-nothing. If one part fails, the entire transaction is rolled back.

---

## 4 Pillars in OOPS
The four pillars of Object-Oriented Programming are:
1. **Encapsulation** – Bundling data and methods together.
2. **Abstraction** – Hiding implementation details, showing only essentials.
3. **Inheritance** – Reusing properties/methods from parent classes.
4. **Polymorphism** – Same interface, different implementations.

---

## What is Inheritance?
Inheritance is an OOP concept where a class (child) derives properties and behaviors from another class (parent), promoting code reuse and hierarchy.

---

## Self Closing Tags in HTML
Self-closing tags do not require a closing tag.  
Examples: `<br>`, `<img>`, `<hr>`, `<input>`, `<meta>`, `<link>`.

---

## Correlated and Non-Correlated Subqueries in SQL
- **Correlated Subquery**: Executes once for each row in the outer query, depends on outer query values.  
- **Non-Correlated Subquery**: Executes independently, result is used by the outer query.

---

## Anchor Tags in HTML and how to open the link in a new tab
The `<a>` tag defines hyperlinks.  
Example:  
```html
<a href="https://example.com" target="_blank">Visit Example</a>
```

href → attribute specifying the link destination

target="_blank" → attribute specifying the link opens in a new tab

---

## Which CSS Has Highest Priority?
CSS priority order:
1. Inline styles (`style=""`) → Highest
2. Internal styles (`<style>`)
3. External stylesheets (`.css` file)
.

---

## CHAR and VARCHAR in SQL
- **CHAR(n)**: Fixed-length string, always stores `n` characters (pads with spaces if shorter).
- **VARCHAR(n)**: Variable-length string, stores only the actual number of characters used.

---

## Args in Python
`*args` allows passing a variable number of positional arguments to a function.  
Example:  
```python
def add(*args):
    return sum(args)
```

---

## Super Method Purpose
`super()` in Python is used to call methods from a parent class, enabling inheritance and method overriding.  
Example:  
```python
class Child(Parent):
    def __init__(self):
        super().__init__()
```

---

## Elements in HTML
HTML elements consist of:
- **Opening tag** (`<p>`)
- **Content** (`Hello World`)
- **Closing tag** (`</p>`)  
Together it is called as element `<p>Hello World</p>`

---

## What is DOCTYPE in HTML?
`<!DOCTYPE html>` declares the document type and version of HTML being used. It helps browsers render the page correctly.

---

## Advantage of External CSS
Advantages:
- Separation of content and design.
- Reusability across multiple pages.
- Easier maintenance and updates.
- Faster page loading (cached CSS files).

---

## TCL Commands in SQL
TCL (Transaction Control Language) commands manage transactions:
- **COMMIT** → Saves changes permanently.
- **ROLLBACK** → Undoes changes since last commit.
- **SAVEPOINT** → Sets a point to rollback to.
- **SET TRANSACTION** → Configures transaction properties.

---