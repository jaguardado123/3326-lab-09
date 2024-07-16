# Lab Assignment 08

In this lab you will practice working with a while loop.

Same as the previous labs, you need to set up your workspace (class and main() method).

## Let's get started!

First, let's look at the name of our .java file in the src/ directory and name your class accordingly and remember to make it **public**. Next, **create your main() method inside your class**.

Now let's begin!

## While Loops

Loops in Java are exactly the same as in C++.

Loos are used to execute a block of code multiple times until a specified condition is met.

Java has two types of while loops, the standard `while loop` and the `do/while loop`. In a standard while loop the condition is checked at the beginning and in a do/while loop the condition is checked at the end.

**While Loop:**
```java
// The condition must return a Boolean value.
while ( condition ) {
	// Code block to be exectured.
}
```

**Do/While Loop:**
```java
do {
	// Code block to be executed.
} while( condition )
```

Both while loops can utilize `break` and `continue` statements.

The `break` statement is used to immediately exit the loop.

The `continue` statement is used to immediately jump to the condition and start a new iteration.

## Random Numbers

To generate a random number in Java you can use the `Math.random()` method. Find out more: https://stackoverflow.com/a/363732/18191837 

## Your program

**Number Guessing Game**

For this assignment you will create a guessing game. `Generate a random number between 0 - 100` and prompt the user to guess that number within that range. `Give the user a total of 3 guesses`. If the `user's guess is correct end the game and congratulate them`, otherwise let the user know if their `guess was too high or too low`. If the user missed all 3 guesses, `let them know they lost and reveal the random number`.

Your output should look like:

```
Welcome to my Number Guessing Game!

Guess a number between 0-100: 50

Oops too high!

Guess a number between 0-100: 10

Oops too low!

Guess a number between 0-100: 25

Oops too low! 

You lost! Correct number was 32.
```

## Submit your assignment

To submit your lab assignment click on the source control icon (3 circles with 2 lines) on your leftside navbar. Next, click on the '+' symbol next to "Changes" to stage your changes. Lastly, add a commit message (ex: "First commit") and click "Commit" then "Push" or "Sync Changes". And you're done!