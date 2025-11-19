# Section 11: Sequence Diagram

- [Introduction](#introduction)
- [Basics of Sequence Diagram](#basics-of-sequence-diagram)
- [Benefits of Sequence Diagram](#benefits-of-sequence-diagram)

---

## Introduction

Sequence diagram shows how objects interact in a step-by-step process over time or in sequential order, focusing on the message
flow between objects.

Represent the interactions between objects. Visualize the order of events and their interactions.

---

## Basics of Sequence Diagram

**Lifeline**

Represents an object or participant in the system and is depicted as a vertical dashed line

Indicates the lifespan of the object during the sequence of events or it indicates the time period during which the particular
object was active and performing action or operation

**Activation**

Describes that time period in which an operation is performed by an element
- represented by a rectangle on the lifeline

**Messages**

Basically a method calls
- represeneted by arrows, on sequential order

**Call Message**

Indicate that one object is invoking an operation on another object
- arrow from calling to called object

**Return Message**

Represent the response of an object to a previously received message
- arrow from the object that response to the object that initiated the call

**Self Message**

Represent the invocation of a method or operation by an object on itself
- represented as a loopback arrow

**Recursive Message**

A self message sent for recursive purpose is called a recursive message

**Create Message**

Represent the creation of a new object

**Destroy / Delete Message**

Represent the destruction or deletion of an object or life

**Synchronous message**

A message that requires a reply from the receiver, and the sender **must wait** for the reply
before continuing

**Asynchronous message**

A message that requires the reply from the receiver but there is **no need of sender to wait** for the reply, 
sender can continue with the next operations.

**Message constraint**

Specify conditions or restrictions on messages
- Guard conditions
- Timing constraints
- Ordering constraints
- Frequency constraints
- Iteration constraints

---

## Benefits of Sequence Diagram

- Communication
- Analysis and Design
- Validation
- Testing
- Maintenance

---






