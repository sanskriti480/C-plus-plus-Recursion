# C++ Experiment 15: Recursion in C++
---

## Aim  
To understand the concept of Inheritance in C++ and its applications:
1. Demonstrating reusability of code through inheritance.
2. Studying different types of inheritance (single, multiple, multilevel, hierarchical, hybrid).
3. Understanding modes of inheritance (public, protected, private).
4. Observing how base class constructors and members are accessed in derived classes.


---

## Tool Used  
VS Code or Programiz Online C++ Compiler.

---

## Objectives  
- To learn the concept of base class and derived class.
- To study how properties and methods of one class can be reused in another.
- To explore public, protected, and private inheritance modes.
- To identify advantages of inheritance in terms of reusability and extensibility.
- To classify different types of inheritance in C++.
  
---

## Theory

### Why C++ is More Efficient than C?
---

- C++ supports Object-Oriented Programming (OOP), which improves code reusability and maintainability.
- Built-in string class makes string manipulation easier than C-style strings.
- Rich Standard Template Library (STL) reduces coding time.
- Better type safety compared to C.
- Function overloading and templates provide flexibility.
- Memory management tools like RAII help prevent leaks.
- Direct support for function overloading and inline functions improves efficiency.

---

### What is inheritance?  
---

1. Inheritance is a feature of Object-Oriented Programming (OOP) in which a new class (derived/child class) acquires the
properties and functionalities of an existing class (base/parent class).
2. It helps in code reusability, since we don’t have to write the same code multiple times.
3. Inheritance establishes a relationship between classes, enabling hierarchies like parent → child.
4. It forms the basis of polymorphism, where derived classes can redefine behaviors of base classes.

---

### What is inheritance important?  
---

1. Promotes code reusability – existing code can be reused in new applications.
2. Enhances maintainability – changes in base class automatically affect derived classes.
3. Supports polymorphism – allows function overriding and runtime flexibility.
4. Provides logical class hierarchies – represents real-world relationships (e.g., Vehicle → Car → SportsCar).
5. Saves time and effort in development.

---

### Syntax:###  
```
class Base {
    // base members
};

class Derived : access-specifier Base {
    // new or extended members
};

```

### Modes of Inheritance  
---

Inheritance in C++ depends on the access specifier used:

Public Inheritance-
1. Public members of base → Public in derived.
2. Protected members of base → Protected in derived.
3. Private members → Not accessible in derived.

Protected Inheritance-
1. Public and Protected members of base → Protected in derived.
2. Private members → Not accessible in derived.

Private Inheritance-
1. Public and Protected members of base → Private in derived.
2. Private members → Not accessible in derived.

---

### Types of inheritance  
---

1. Single inheritance-
In single inheritance, a class is allowed to inherit from only one class. i.e. one subclass is inherited by one base class only.
2. Multiple inheritance-
Multiple Inheritance is a feature of C++ where a class can inherit from more than one class. i.e one subclass is inherited from more than one base class.
3. Multilevel inheritance-
In this type of inheritance, a derived class is created from another derived class.
4. Hierarchical Inheritance-
In this type of inheritance, more than one subclass is inherited from a single base class. i.e. more than one derived class is created from a single base class.

---

### Pointer arithmetic rules  
---

- Incrementing a pointer moves it to the next element of its type (ptr++).
- Subtracting two pointers gives the number of elements between them.
- Pointer arithmetic is valid only within the same array or memory block.

---

### Advantages of inheritance 
---

- Code Reusability – Reuse base class functionality in derived classes.
- Extensibility – Add new features to existing classes without rewriting.
- Saves Time & Effort – Reduces duplication.
- Supports Polymorphism – Enables function overriding and dynamic behavior.
- Organized Structure – Represents real-world hierarchies clearly.

---

### Disadvantages of inheritance
---

- Increased Complexity – Multiple levels of inheritance may be difficult to manage.
- Tight Coupling – Derived class depends heavily on base class.
- Unexpected Behavior – Overridden methods may cause errors if not carefully implemented.
- Performance Issues – Virtual function tables (used in polymorphism) add overhead.
- Not Always the Best Choice – Sometimes composition (has-a relationship) is better than inheritance (is-a relationship).
  
---



## Concepts Used  
---

- Base and derived class relationships.
- Modes of inheritance (public, protected, private).
- Types of inheritance (single, multiple, multilevel, hierarchical, hybrid).
- Constructor and destructor call order in inheritance.
- Function overriding and polymorphism.

---

## Conclusion
---

- In this experiment, we studied Inheritance in C++, including its types and modes.
- We understood how one class can acquire the properties of another, improving reusability and extensibility.
- We also explored the advantages and limitations of inheritance.
- Overall, inheritance is a powerful concept in OOP that helps in writing modular, maintainable, and reusable code.

---
