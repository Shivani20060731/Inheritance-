# Inheritance-
AIM

To study and implement inheritance in C++.

SOFTWARE USED

VS Code



OBJECTIVES

1. Code Reusability – Reuse functionality of existing classes without rewriting.


2. Data Hiding & Access Control – Provide controlled access using public, protected, private.


3. Extensibility – Extend existing classes with new features.


4. Hierarchical Classification – Represent IS-A relationships (e.g., Student IS-A Person).


5. Polymorphism – Support runtime behavior using virtual functions.


6. Maintainability – Base class changes automatically reflect in derived classes.


7. Readability & Organization – Improves program structure and clarity.




ALGORITHM

1. Define the base class with common members.


2. Use : with public, protected, or private for inheritance.


3. Define derived class with extra or overridden members.


4. Create objects of the derived class.


5. Access base members using derived class objects.


6. Implement constructors and destructors in both classes.




THEORY

1. Definition
Inheritance is an OOP feature where one class (derived) acquires the properties and behaviors of another (base). It models IS-A relationships.


2. Why Use Inheritance



Code reuse

Extensibility

Logical modeling

Polymorphism

Maintainability


3. Types of Inheritance



Single: One base → One derived

Multiple: Multiple bases → One derived

Multilevel: Chain of inheritance (A→B→C)

Hierarchical: One base → Many derived

Hybrid: Combination of the above


4. Modes of Inheritance



public: base public → derived public; base protected → derived protected

protected: base public/protected → derived protected

private: base public/protected → derived private


5. Key Concepts


Constructors run base first → derived next; destructors in reverse.

Virtual functions enable runtime polymorphism.

Pure virtual functions create abstract classes.

Diamond problem solved with virtual inheritance.



FLOWCHART

Example: Multilevel

[Person] → [Student] → [GraduateStudent]

Example: Hierarchical

[Vehicle]
        /    |    \
   [Car] [Bike] [Bus]


CONCLUSION

Inheritance helps reuse and extend code while keeping it structured.
It models real-world relationships (IS-A).
Supports polymorphism and improves maintainability.
Care is needed to avoid issues like ambiguity in multiple inheritance and overusing inheritance where composition is better.

