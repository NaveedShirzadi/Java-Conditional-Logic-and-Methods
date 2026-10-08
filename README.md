# Java Homework 2: Classes, Methods, and Inheritance

A small Java program with eight exercises about how classes and methods behave. `Main.java` runs them in order and prints the results.

## The exercises

| Exercise | Topic |
|---|---|
| 1 | A `Point` class with constructors and a `move` method |
| 2 | Java passes arguments by value: a number changed inside a method is unchanged outside, and reassigning an object parameter does not change the caller's object |
| 3 | The no argument `Point` constructor, which creates the point (0, 0) |
| 4 | A `Microwave`, which is a kind of `Device` with a maximum cooking time |
| 5 | A method with a variable number of arguments (`sumCoordinates`) that adds up x values, called with separate points and with an array |
| 6 | Overriding `printDescription` and calling the parent version with `super` |
| 7 | Polymorphism: a `Device` variable that holds a `Microwave` runs the Microwave's version of the method |
| 8 | Using `instanceof` and a cast to call a method that only a `Microwave` has (`heatFood`) |

## Files

- `src/main/java/Main.java` runs the exercises
- `src/main/java/Point.java` is the point class
- `src/main/java/Device.java` is the parent class
- `src/main/java/Microwave.java` extends `Device`
- `pom.xml` is the Maven setup (Java 21)

## How to run

In IntelliJ, open the folder that contains `pom.xml` and run `Main`.

From the command line, with JDK 21 or newer:

```
javac -d out src/main/java/*.java
java -cp out Main
```

The default branch of this repository is `trunk`.
