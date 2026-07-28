# Exercise 2 – Understanding Objects

## Objective

Apply your understanding of classes, objects, fields, methods, constructors, state, and behaviour to a different Java class.

---

## Car Class

```java
public class Car {

    private String registrationNumber;
    private String colour;
    private boolean available;

    public Car(String registrationNumber, String colour) {
        this.registrationNumber = registrationNumber;
        this.colour = colour;
        this.available = true;
    }

    public void startEngine() {
        System.out.println("Engine started.");
    }

    public void stopEngine() {
        System.out.println("Engine stopped.");
    }
}
```

---

## Questions

### Question 1

List all the fields in the Car class.

---

### Question 2

List all the methods.

---

### Question 3

Identify the constructor.

Explain how you know it is the constructor.

---

### Question 4

Which fields represent the state of the Car?

Explain your answer.

---

### Question 5

Which methods represent the behaviour of the Car?

Explain your answer.

---

### Question 6

Add one new behaviour to the Car class.

Examples:

- lockDoors()
- unlockDoors()
- drive()
- park()

Write only the Java method.

---

## Reflection

1. What is the difference between a field and a method?

2. Why is the registration number stored as a field instead of inside a method?

3. Could two Car objects have different registration numbers? Explain.