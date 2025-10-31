# Java OOP — Interfaces Project

This project is part of the **Hexlet Java OOP course**.  
It demonstrates the use of **interfaces**, **polymorphism**, and **abstraction** in Java by modeling real-world objects and implementing the `CharSequence` interface.

---

## 🧩 Project Overview
The main goal of this assignment is to practice designing flexible, extensible systems using interfaces instead of rigid class hierarchies.

Key learning points:
- Declaring and implementing Java interfaces
- Using polymorphism to interact with different object types through a shared contract
- Designing clean, testable object-oriented structures
- Implementing Java’s built-in `CharSequence` interface manually

---

## 🏗️ Main Classes
- **`Home`** – interface defining a common contract for different housing types  
- **`Flat`** – implementation representing an apartment  
- **`Cottage`** – implementation representing a private house  
- **`ReversedSequence`** – a custom implementation of the standard `CharSequence` interface that returns characters in reverse order

These examples illustrate how **interfaces enable polymorphism**, allowing different classes to be processed in a unified way.

---

## 🧪 Run Tests
To verify correctness locally:
```bash
./gradlew clean test
