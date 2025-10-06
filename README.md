## 📘 Python OOP Exercises

This project demonstrates basic **Object-Oriented Programming (OOP)** concepts in Python, including **inheritance**, **modules**, and **class methods**.

---

### 🧮 Q1: Course Inheritance Example

**File:** `course.py`

This program defines a base class `Course` and two subclasses `CoreCourse` and `ElectiveCourse`.
It demonstrates how inheritance allows child classes to extend the functionality of a parent class.

#### **Code Summary**

* `Course`: Base class containing attributes like course code, name, and credits.
* `CoreCourse`: Inherits from `Course` and adds a `required` attribute.
* `ElectiveCourse`: Inherits from `Course` and adds an `elective_type` attribute.
* Both subclasses use the inherited `display()` method.

#### **Sample Output**

```
CS101 - Intro to CS (3 credits)
ENG201 - Creative Writing (2 credits)
```

---

### 🧑‍💼 Q2: Employee Module Example

**Files:**

* `employee.py` → Module file defining the `Employee` class
* `main.py` → Script that imports and uses the module

#### **Code Summary**

* `Employee` class has:

  * Attributes: `name`, `salary`
  * Methods: `get_name()` and `get_salary()`
* The `main.py` program imports the class from the module, creates an object, and displays its details.

#### **Sample Output**

```
Employee Name: Alice Johnson
Employee Salary: 60000
```

---

### 🛠️ How to Run

1. Save the following files in the same directory:

   * `course.py`
   * `employee.py`
   * `main.py`

2. Run each file from your terminal or IDE:

   ```bash
   python course.py
   python main.py
   ```

---

### 🧠 Concepts Covered

* Class creation and instantiation
* Inheritance and method reuse
* Module import and usage
* Encapsulation using getter methods

---

### 📄 Author

ASHIBA B
Python Programming – OOP Practice Exercises

---

