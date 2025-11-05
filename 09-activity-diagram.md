# Section 9: UML Activity Diagram

- [Introduction](#introduction)
- [Basics of Activity Diagram](#basics-of-activity-diagram)
- [Benefits of Activity Diagram](#benefits-of-activity-diagram)

---

## Introduction

Activity Diagram is a behavioral diagram used to model the flow of 
- actions
- activities
- decisions in a system or process

Typically used to model the business processes, workflows and system behaviors

Useful for analyzing, designing and documenting the sequence of activities for a process / use case

---

## Basics of Activity Diagram

**Activities**
- Represent the steps or actions that are taken in the system or process

**Initial State**
- Beginning of a set of actions

**Control Flow**
- Show the order in which activities are executed in the system or process

**Decision Nodes**
- Show conditional logic in the system or process

**Fork Nodes**
- Split a single control flow into multiple flows

**Merge Nodes**
- Combine two or more incoming control flows into a single outgoing flow
- **Does not wait** for all incoming flows to arrive before continuing, and it **does not synchronize** the incoming flows
- Diamond node

**Join Nodes**
- Synchronize two or more incoming control flows into a single outgoing flow
- Bar nodes with multiple incoming arrows and a single outgoing arrow
- The join node **waits for all incoming flows** to arrive and then **synchronizes** them before continuing along the outgoing flow

**Swimlanes**
- Divide the activities or actions into categories or groups

**Final State**
- Stage where all the control flows and object flows end

---

## Benefits of Activity Diagram

- Communication
- Analysis and Design
- Validation
- Implementation
- Training and Support

---


