# Complex Number Addition using Operator Overloading in C++

This project demonstrates **operator overloading in C++** by implementing addition of **complex numbers** using a user-defined class.
It shows how the `+` operator can be overloaded to work with objects.

---

## 📌 Objective

To understand and implement:
- Operator overloading
- Classes and objects
- Constructor initialization
- Passing objects by reference

---

## 🧠 Concepts Used

- Class and Object  
- Constructor with default arguments  
- Operator Overloading (`+`)  
- `const` correctness  
- Encapsulation  

---

## 🧾 Program Description

- The `Complex` class stores:
  - `real` → real part of the complex number
  - `imag` → imaginary part of the complex number
- The `+` operator is overloaded to add two complex numbers
- The result is returned as a new `Complex` object
- The `display()` function prints the complex number in standard format

---

## 🧩 Class Structure

### Data Members
- `int real`
- `int imag`

### Member Functions
- `Complex(int r = 0, int i = 0)` → Constructor  
- `Complex operator+(const Complex& c)`  
- `void display()`  

---

## ▶️ Sample Input (From Code)

```cpp
Complex c1(3, 4);
Complex c2(1, 2);
