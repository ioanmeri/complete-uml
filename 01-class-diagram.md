# Section 1: UML Class Diagram

## Class Diagram

The class diagram describes the classes of the applications been modeled along with their relationship to one another
- represent the blueprint of the code

---

### Classes

- Building Blocks
- Represents Objects or Entities
- Define Attributes & Behaviours

---

### Visibility

- public: +
  - Accessible anywhere and within System
- private: -
  - Accessible in a class that defines it
- protected: #
  - Accessible in a class that defines it OR Subclass
- package: ~
  - Accessible within same package

---

### Associations

How objects of one class interacts with objects of another class and define the multiplicity of the relationship
- One to One
- One to Many
- Many to One
- Many to Many

---

### Inheritance

Hierarchical relationship between classes, where a subclass inherites attributes and methods from its parent class

Arrow pointing from the subclass to the superclass with an unfilled triange at the arrow head

Example: Animal ⬅️ Dog

---

### Aggregation

Represents a whole-part relationship between two classes

**Partclass can exist independently** of the whole class

Relationship type
- has a
- is part of

It's a one directional relationship

Examples
- Wallet - Money (money can exist without wallet)
- Car - Wheel (wheel can independently move with e.g. the bike)

---

### Composition

Represents a **strong whole-part relationship** between two classes

Part cannot exist independently of the Whole

Examples 
- HumanBody (filled diamond) - Heart
- Folder (filled diamond) - File

symbolized with a filled diamond

---

### Realization

How one element implements the behavior specified by another element.

Commonly used to model the relationship between an interface / Abstract class and it's implementation

How class that **implements interface** provides concrete implementations for the methods defined by the interface

How a subclass provides concrete implementations for the abstract methods defined by the **Abstract** class

Example: Car ➡️ IVehicle

symbolized with a dashed line with an unfilled arrow head


**Realization vs Inheritance**

- Realization
  - Implements
  - Providing concrete implementations for methods defined by an interface or an abstract class
- Inheritance
  - Inherit
  - Inheriting properties and behaviors from a superclass and possibly adding more to  it or overriding them in the subclass
  
---

### Multiplicity

You can specify the number of instances of one class that are linked with the instance of another class
- One-to-One (1:1)
  - HumanBody - Nose
  - 1..1
- One-to-Many (1:N)
  - Department - Employee
  - 1..*
- Many-to-One (N:1)
  - CreditCard - Person
  - *..1
- Many-to-Many (N:N)
  - Student - Course
  - (*)

---

