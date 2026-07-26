Exercise 1 - Understanding Objects

## Objective

Learn to identify the different parts of a Java class and understand the difference between state and behaviour.

---

## Robot Class

```java
public class Robot {

    private String name;
    private int health;
    private int shields;

    public Robot(String name) {
        this.name = name;
        this.health = 100;
        this.shields = 5;
    }

    public void moveForward() {
        System.out.println(name + " moved forward.");
    }

    public void turnLeft() {
        System.out.println(name + " turned left.");
    }
}
```

---

## Questions

### Question 1

Identify all the fields in the Robot class.

---

### Question 2

Identify all the methods.

---

### Question 3

Which method is the constructor?

Explain how you know.

---

### Question 4

Which members represent the Robot's **state**?

Explain why.

---

### Question 5

Which members represent the Robot's **behaviour**?

Explain why.

---

### Question 6

Add one new behaviour to the Robot class.

Examples:

- turnRight()
- moveBackward()
- fire()
- recharge()

Write the Java method.



Reflection
---

## Reflection

1. Can one class create many objects?

2. Does every Robot object have its own values for name, health and shields?

3. Why are fields private?

4. Why do methods belong inside the Robot class?

5. If you created two Robot objects, would changing one Robot's health affect the other? Why?

