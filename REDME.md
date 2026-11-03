# JavaScript Program to Check Even or Odd Number

## Objective
The objective of this assignment is to create a JavaScript program that checks whether a given number is even or odd.

## Tasks
- Write a JavaScript program to check whether a number is even or odd.
- Use four different variables.
- Use `console.log()` to display the result.
- Use an `if-else` statement.

## Source Code

```javascript
// Declare four variables
let number1 = 5;
let number2 = 10;
let remainder1 = number1 % 2;
let remainder2 = number2 % 2;

// Check first number
if (remainder1 == 0) {
    console.log("The number " + number1 + " is even.");
} else {
    console.log("The number " + number1 + " is odd.");
}

// Check second number
if (remainder2 == 0) {
    console.log("The number " + number2 + " is even.");
} else {
    console.log("The number " + number2 + " is odd.");
}
```

## Output

```text
The number 5 is odd.
The number 10 is even.
```

## Explanation

- `let`: Used to declare variables.
- `%`: Modulus operator, which returns the remainder.
- `if`: Checks whether a condition is true.
- `else`: Executes when the condition is false.
- `console.log()`: Displays the output.

## Conclusion

Thus, the JavaScript program successfully checks whether the given numbers are even or odd using an if-else statement.