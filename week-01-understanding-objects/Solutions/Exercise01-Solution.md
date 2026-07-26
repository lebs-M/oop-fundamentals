# Exercise 1 Solution

## Question 1

Fields:

- name
- health
- shields

These are fields because they store information about each Robot object.

---

## Question 2

Methods:

- Robot(...)
- moveForward()
- turnLeft()

These represent actions or behaviours.

---

## Question 3

Constructor:

```java
public Robot(String name)


A constructor has the same name as the class and does not have a return type. It is called when a new Robot object is created.

---

## Question 4

State:

- name
- health
- shields

These values describe the Robot.

---

## Question 5

Behaviour:

- moveForward()
- turnLeft()

These methods describe what the Robot can do.

---

## Question 6

One possible solution:

```java
public void moveBackward() {
    System.out.println(name + " moved backward.");
}
