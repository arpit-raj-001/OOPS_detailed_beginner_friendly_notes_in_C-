# 🚀 Complete C++ Object-Oriented Programming (OOP)

<p align="center">
  <img src="https://img.shields.io/badge/Language-C%2B%2B-blue?style=for-the-badge&logo=cplusplus" />
  <img src="https://img.shields.io/badge/Focus-Object--Oriented%20Programming-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Notes-21%20Detailed%20PDFs-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Purpose-Interview%20Preparation-success?style=for-the-badge" />
</p>

<p align="center">
  <b>A structured and detailed journey through C++ Object-Oriented Programming — from fundamental principles to advanced language internals.</b>
</p>

---

## 📖 About This Repository

Object-Oriented Programming is much more than learning classes, objects, inheritance, and polymorphism. To develop a strong understanding of OOP in C++, it is important to understand **why these concepts exist, how the language implements them, what happens internally, and when to use them in practical software design.**

This repository contains a collection of **21 detailed PDF notes**, organized into a progressive learning sequence.

The material starts with the limitations of traditional programming approaches, builds a foundation in classes and object-oriented principles, explores inheritance and polymorphism, and eventually moves into advanced topics such as:

- Virtual function dispatch and its internal implementation.
- VTables, VPtrs, and runtime polymorphism.
- Object slicing and inheritance behavior.
- Copy constructors and assignment operators.
- Shallow copying versus deep copying.
- Rule of Three, Rule of Five, and move semantics.
- Composition, aggregation, and association.
- Contract design and advanced class behavior.

The goal is not simply to memorize interview definitions, but to develop the ability to **reason about C++ code, understand object behavior, identify subtle bugs, and design better object-oriented systems.**

---

# 🗺️ Learning Roadmap

The notes are divided into four broad learning stages.

<details open>
<summary><b>🟢 Stage 1 — OOP Foundations (PDF 01–05)</b></summary>

### Understanding the motivation and fundamentals of OOP

Before learning the mechanics of OOP, we first explore the problems that motivated its development.

| PDF | Topic | Knowledge Covered |
|:---:|---|---|
| **01** | Problems with Functional Programming | Limitations of traditional procedural/functional-style program organization, handling complexity, data and function separation, and motivation for OOP. |
| **02** | Why OOP? Structs, Arrays and Beyond | Understanding how structs and arrays organize data, their limitations in larger programs, and how classes combine data with behavior. |
| **03** | Constructors and Destructors | Object initialization, default and parameterized constructors, constructor execution, destructor behavior, object lifetime, and resource cleanup. |
| **04** | Encapsulation and Access Modifiers | Data hiding, public/private/protected access, controlled access to class members, and maintaining object integrity. |
| **05** | Structs, Friend Functions and Classes | Differences between structures and classes in C++, default access behavior, friend functions, and controlled access to private members. |

**After this stage:** You should understand the motivation behind OOP, the role of classes and objects, object initialization, encapsulation, and access control.

</details>

<details open>
<summary><b>🔵 Stage 2 — Inheritance and Its Implementation (PDF 06–11)</b></summary>

### Understanding relationships between classes and derived objects

This stage explores how classes can reuse and extend existing behavior, along with the complexities that arise when inheritance becomes more advanced.

| PDF | Topic | Knowledge Covered |
|:---:|---|---|
| **06** | Inheritance Modes and Types | Public, protected, and private inheritance; single, multiple, multilevel, hierarchical, and hybrid inheritance. |
| **07** | Implementing Inheritance and Aggregation | Implementing parent-child relationships, constructor and destructor execution in inheritance, and relationships between independent objects. |
| **08** | More Inheritance Concepts, Slicing and Virtual Functions | Advanced inheritance behavior, derived-to-base conversion, object slicing, and the motivation for virtual functions. |
| **09** | Runtime Polymorphism and Virtualization | Runtime polymorphism, base-class pointers and references, virtual function behavior, and dynamic method dispatch. |
| **10** | Override, Virtual Destruction and Abstract Classes | Function overriding, the `override` specifier, virtual destructors, abstract classes, and pure virtual functions. |
| **11** | Upcasting, Downcasting, `dynamic_cast` and `static_cast` | Type conversions in inheritance hierarchies, safe and unsafe downcasting, RTTI, and C++ casting operators. |

**After this stage:** You should be able to implement inheritance hierarchies, understand runtime polymorphism, work with base-class pointers and references, and reason about type conversions.

</details>

<details open>
<summary><b>🟣 Stage 3 — Polymorphism, Templates and Abstraction (PDF 12–15)</b></summary>

### Exploring compile-time behavior, generic programming and class contracts

This stage expands beyond inheritance-based polymorphism and introduces mechanisms that allow C++ programs to achieve flexibility at compile time and through abstraction.

| PDF | Topic | Knowledge Covered |
|:---:|---|---|
| **12** | Compile-Time Polymorphism and Function Overloading | Function overloading, parameter-based overload resolution, compile-time polymorphism, and how the compiler selects functions. |
| **13** | Constructor Overloading and Templates | Multiple constructor definitions, constructor selection, function templates, class templates, generic programming, and template specialization. |
| **14** | Abstraction | Hiding implementation complexity, exposing essential behavior, abstract interfaces, pure virtual functions, and separation of interface from implementation. |
| **15** | Contract Design and the `const` Keyword | Designing class contracts, preconditions and postconditions, invariants, const correctness, const member functions, and controlling unintended modification. |

**After this stage:** You should understand compile-time and runtime polymorphism, generic programming, abstraction, and how to design classes with clear behavioral contracts.

</details>

<details open>
<summary><b>🔴 Stage 4 — Advanced C++ OOP Internals (PDF 16–17, 19–22)</b></summary>

### Understanding what happens beneath the surface

This stage revisits important OOP mechanisms at a deeper level, focusing on implementation details, object representation, memory ownership, and resource management.

| PDF | Topic | Knowledge Covered |
|:---:|---|---|
| **16** | Virtual Destructors — Deep Dive | Destruction through base-class pointers, destructor chaining, polymorphic object cleanup, and the importance of virtual destructors. |
| **17** | Object Slicing: Pointers and References | How object slicing occurs, why derived-class information is lost during base-object copying, and how pointers and references avoid slicing. |
| **19** | VTable, VPtr and Virtual Dispatch | Internal implementation of virtual functions, virtual tables, virtual pointers, dynamic dispatch, and runtime method resolution. |
| **20** | Shallow Copy, Deep Copy and Copy Constructor | Member-wise copying, pointer ownership, dynamically allocated memory, copy constructor implementation, and deep-copy behavior. |
| **21** | Rule of 3, Rule of 5, Copy and Move Semantics | Copy constructor, copy assignment, destructor, move constructor, move assignment, `std::move`, resource transfer, and modern C++ resource management. |
| **22** | Composition, Aggregation and Association | Object relationships, ownership models, object lifetime dependencies, composition versus aggregation, and association between independent objects. |

**After this stage:** You should be able to reason about object memory, virtual dispatch, polymorphic destruction, copying, moving, and ownership relationships in C++.

</details>

---

# 🧩 Complete Knowledge Map

The following map summarizes the major areas explored throughout the notes.

```text
                    C++ OBJECT-ORIENTED PROGRAMMING
                                  |
           +----------------------+----------------------+
           |                      |                      |
       FOUNDATIONS            INHERITANCE            POLYMORPHISM
           |                      |                      |
     Classes & Objects      Inheritance Modes       Compile-Time
     Constructors           Derived Classes         Function Overloading
     Destructors             Aggregation             Constructor Overloading
     Encapsulation           Upcasting               Templates
     Access Modifiers        Downcasting             Runtime
     Friend Functions        Object Slicing          Virtual Functions
                             Abstract Classes        Function Overriding
                             Virtual Destructors     Dynamic Dispatch
                                                           |
                              +----------------------------+
                              |
                       ADVANCED C++ INTERNALS
                              |
                +-------------+-------------+
                |             |             |
             VTable         Copying       Object Design
             VPtr           Deep Copy     Composition
             Dispatch       Shallow Copy  Aggregation
                            Copy Ctor     Association
                            Rule of 3
                            Rule of 5
                            Move Semantics
                            Const Correctness
                            Contract Design
