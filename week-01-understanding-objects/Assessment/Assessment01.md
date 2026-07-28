# Week 1 Assessment – Understanding Objects

## Instructions

Work independently.

Do not use previous exercises while completing this assessment.

Read the code carefully before answering the questions.

---

## Student Class

```java
public class Student {

    private String studentNumber;
    private String name;
    private int age;

    public Student(String studentNumber, String name, int age) {
        this.studentNumber = studentNumber;
        this.name = name;
        this.age = age;
    }

    public void study() {
        System.out.println(name + " is studying.");
    }

    public void submitAssignment() {
        System.out.println(name + " submitted an assignment.");
    }
}
```

---

## Question 1

Identify every field.

(3)

---

## Question 2

Identify every method.

(3)

---

## Question 3

Which method is the constructor?

Explain why.

(2)

---

## Question 4

List the Student's state.

Explain your answer.

(4)

---

## Question 5

List the Student's behaviour.

Explain your answer.

(4)

---

## Question 6

Add one new behaviour to the Student class.

Examples include:

- attendClass()
- writeExam()
- graduate()

Write the complete Java method.

(4)

---

## Question 7

Explain the difference between a class and an object using your own words.

(5)

---

## Bonus Challenge (Optional)

If the university has 500 students, do we need to create 500 Student classes?

Explain your answer.

---

Total: 25 marks