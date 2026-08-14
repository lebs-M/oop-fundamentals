# Week 2 – Encapsulation

## Workshop Theme

**Reinforcing OOP Fundamentals: Encapsulation**

This workshop focuses on how objects protect and control their own state.

Before adding more functionality to an application, it is important to understand how objects should manage the data they own.

---

## Learning Objectives

By the end of this workshop, you should be able to:

- Explain what encapsulation means.
- Understand the difference between `private` and `public`.
- Explain why object fields are commonly made `private`.
- Understand the purpose of getters.
- Understand when setters are appropriate and when they are not.
- Protect an object's state from invalid changes.
- Add behaviour that allows an object to safely modify its own state.
- Explain why validation can belong inside the object that owns the data.

---

## Topics

This workshop covers:

- `private` vs `public`
- Encapsulation
- Getters
- Setters
- Protecting object state
- Object behaviour
- State validation

---

## Why Encapsulation?

An object should have control over the state that it owns.

Consider a Robot with shields:

```java
robot.shields = -100;
```

If `shields` is publicly accessible, another class can directly change the Robot's state without the Robot having any control over whether the change is valid.

Encapsulation allows the object to control how its state is accessed and changed.

Instead of directly changing the state:

```text
Other Object
     |
     v
  Robot
     |
     v
Changes its own state
```

The Robot can provide behaviour that controls the change.

---

## Exercises

### Exercise 1 – Identify the Problem

Identify the problems with a class whose fields are publicly accessible.

You will consider:

- Which fields are exposed.
- Why public fields can be dangerous.
- How another class could modify an object's state.
- How `private` changes the design.

---

### Exercise 2 – Refactor the Robot

You will refactor a Robot class so that:

- Its fields are private.
- Its state can be read through appropriate methods.
- Its state can be changed through appropriate behaviour.
- Other classes cannot directly modify its fields.

You will also consider whether every field should automatically have a setter.

---

### Exercise 3 – Validation Challenge

You will work with a `BankAccount` class.

The account must protect its balance by enforcing rules such as:

- Deposits cannot be negative.
- Withdrawals cannot be negative.
- A withdrawal cannot exceed the current balance.

The goal is to understand how an object can protect its own state.

---

## Assessment

The Week 2 assessment focuses on encapsulating a `Vehicle` class.

You will be expected to:

- Make the Vehicle's state private.
- Provide appropriate methods for accessing its state.
- Provide behaviour for changing its availability.
- Validate its rental rate.
- Explain why the fields should not remain public.

---

## Reflection

After completing the exercises, consider the following:

- What does encapsulation mean in your own words?
- Why should an object's fields usually not be directly accessible?
- What is the difference between accessing state and changing state?
- Should every field have a setter?
- Who should be responsible for protecting an object's state?
- How does encapsulation help prevent invalid object state?

---

## Submission Checklist

Before submitting your work:

- [ ] Fields are appropriately `private`.
- [ ] Other classes cannot directly modify the object's state.
- [ ] Required methods have been implemented.
- [ ] Validation rules have been implemented.
- [ ] The code compiles.
- [ ] You can explain your design decisions.
- [ ] You have completed the reflection questions.

---

## Key Principle

> **An object should control access to and changes to the state that it owns.**

The goal of this workshop is not simply to use getters and setters. The goal is to understand **why an object should protect its own state and how encapsulation helps us design better objects.**