### **What is Dictionary (dict)**
- A `dict` in Python stores data as **key-value pairs**.
- Example: `{"name": "Abhishek", "age": 24}`.
- Keys must be unique; values can be anything.

---

### **Keys and Accessing Them**
- Access value: `my_dict["name"]`.
- Get all keys: `my_dict.keys()`.
- Convert keys to list: `list(my_dict.keys())`.

---

### **Mutable vs Immutable**
- **Mutable**: Can be changed (e.g., `list`, `dict`, `set`).
- **Immutable**: Cannot be changed (e.g., `tuple`, `str`, `int`).

---

### **For Loop vs While Loop**
- **For loop**: Iterates over a sequence (`for i in range(5):`).
- **While loop**: Runs until a condition is false (`while x < 5:`).

---

### **Merge in Git**
- Combines changes from one branch into another.
- Example: `git merge feature-branch` merges into current branch.

---

### **Switch Case**
- Python doesn’t have a direct switch-case.
- Use `match-case` (Python 3.10+):
  ```python
  match x:
      case 1: print("One")
      case 2: print("Two")
  ```

---

### **Polymorphism**
- Same function name works differently depending on object type.
- Example: `len("abc")` → 3, `len([1,2,3])` → 3.

---

### **Negative Indexing**
- Access elements from the end of a sequence.
- Example: `arr[-1]` → last element.

---

### **String Methods**
- Common ones:  
  - `.upper()` → uppercase  
  - `.lower()` → lowercase  
  - `.strip()` → remove spaces  
  - `.split()` → split into list  

---

### **Object to Abstract Class**
- Abstract class defines methods but doesn’t implement them.
- Objects of subclasses implement those methods.
- Example: `ABC` module in Python.

---

### **Staging Area (Git)**
- Temporary area before committing changes.
- Add files: `git add file.py`.
- Commit from staging: `git commit -m "message"`.

---

### **pwd Command**
- Stands for **Print Working Directory**.
- Shows current directory in Linux/Unix.

---

### **Constructor**
- Special method `__init__` in Python.
- Runs automatically when creating an object.
- Example:
  ```python
  class Car:
      def __init__(self, brand):
          self.brand = brand
  ```

---

### **Need of a Class**
- Classes group data (**attributes**) and behavior (**methods**) together.
- Helps in **code reusability, organization, and abstraction**.

---
