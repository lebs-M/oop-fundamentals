public class Robot {

    public String name;
    public int shields;
    public int shots;

    public Robot(String name) {
        this.name = name;
        this.shields = 5;
        this.shots = 5;
    }
}

Question 1

Which fields are exposed directly?

Question 2

What is wrong with making these fields public?

Question 3

What could another class do to the Robot's state?


Question 4

Change the fields so that the Robot controls access to its own state.


Question 5

What methods would another class need in order to read the Robot's information?


