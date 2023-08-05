# Overview
This page is about math relevant functions or methods.

# Random
1. Random Integer: In order to get an integer value from `[0, x)`.
    ```java
    int randomInt = new Random().nextInt(x);
    ```


# Round
1. rounds downward: Rounds a number downward to the nearest integer.
    ```java
    /**
     * [0, 1) -> 0, [1, 2) -> 1, ... , [x - 1, x) -> x - 1, [x, x + 1) -> x;
     * [-1, 0) -> -1, [-2, -1) -> -2, ... , [-x - 1, -x) -> -x - 1;
    */
    int integer = Math.floor(num);
    ```