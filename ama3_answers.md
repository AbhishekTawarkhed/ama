## What is pwd?
- **Definition:** pwd stands for **print working directory** in Unix/Linux systems.
- **Usage:** Displays the absolute path of the current working directory.


---

## RGB color for black
- **RGB Value:** rgb(0, 0, 0)
- **Explanation:** All three channels (Red, Green, Blue) set to 0 produce pure black.
- **Hex Equivalent:** #000000

---

## What is flex-wrap in CSS?
- **Definition:** Determines whether flex items are forced onto one line or can wrap onto multiple lines.
- **Values:**
  - nowrap → Default, all items stay on one line.
  - wrap → Items wrap onto new lines as needed.
  - wrap-reverse → Items wrap onto new lines but in reverse order.


---

## Explain <img> tag and its properties
- **Purpose:** Embeds images into HTML documents.
- **Key Attributes:**
  - src → Path to the image file.
  - alt → Alternative text for accessibility and SEO.
  - width / height → Dimensions of the image.
- **Example:**
  ```html
  <img src="photo.jpg" alt="A scenic view" width="600" height="400">
  ```

---

## What is a class in Python?
- **Definition:** A class is a blueprint for creating objects (instances).
- **Features:**
  - Encapsulates data (attributes) and behavior (methods).
  - Supports object-oriented programming concepts like inheritance and polymorphism.

---

## Class and ID in HTML
- **Class (class):**
  - Used to group multiple elements for styling or scripting.
  - Can be reused across multiple elements.
  - Selector in CSS: `.classname`
- **ID (id):**
  - Unique identifier for a single element.
  - Should not be repeated.
  - Selector in CSS: `#idname`

---

## Grid row and grid column in CSS
- **Definition:** Properties used in CSS Grid to define how elements span rows and columns.
- **Properties:**
  - grid-row-start, grid-row-end
  - grid-column-start, grid-column-end
- **Shorthand:**
  - grid-row: 1 / 3;
  - grid-column: 2 / 4;


---

## A and C in ACID (SQL)
- **A – Atomicity:** Ensures that a transaction is all-or-nothing. If one part fails, the entire transaction fails.
- **C – Consistency:** Guarantees that a transaction brings the database from one valid state to another, maintaining rules and constraints.

---

## What is Z-index in CSS?
- **Definition:** Controls the stack order of elements.
- **Behavior:** Higher `z-index` values appear in front of lower ones.

---

## Universal selector in CSS
- **Selector:** *
- **Purpose:** Applies styles to all elements.
- **Example:**
  ```css
  * {
    margin: 0;
    padding: 0;
  }
  ```

---

## Single Responsibility Principle (SRP)
- **Definition:** A class should have only one reason to change, meaning it should only handle one responsibility.
- **Benefit:** Improves maintainability, readability, and reduces coupling.
- **Example:**   A class that handles **user authentication** should not also handle **logging**.

---

## How do you go to the same section in the same website?
- **Method:** Use anchor links with `id`.
- **Example:**
  ```html
  <a href="#about">Go to About Section</a>

  <div id="about">
    <h2>About Us</h2>
  </div>
  ```

---

## Make circles in CSS
- **Method:** Use `border-radius: 50%` on a square element.
- **Example:**
  ```css
  .circle {
    width: 100px;
    height: 100px;
    background: red;
    border-radius: 50%;
  }
  ```

---

## How many bytes for RGB value?
- **Explanation:** Each channel (Red, Green, Blue) uses 1 byte (0–255).
- **Total:** 3 bytes for RGB.
- **Example:** rgb(255, 0, 0) → Red color.

---

## Relative and Absolute (CSS positioning)
- **Relative:**
  - Positioned relative to its normal position.
  - Example: position: relative; top: 10px;
- **Absolute:**
  - Positioned relative to the nearest positioned ancestor (not static).
  - Example: position: absolute; top: 50px; left: 100px;
