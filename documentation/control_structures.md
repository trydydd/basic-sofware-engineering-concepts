# Control Structures

Control structures are used to control the flow of a program. The most common control structures are:

## Conditional statements
- `if`: The `if` statement is used to test a condition and execute a block of code if the condition is true. Use `if` when you want to perform a specific action only if a certain condition is met.
- `elif`: The `elif` (short for "else if") statement is used to test a condition only if the previous `if` or `elif` statement evaluated to false. Use `elif` when you want to test multiple conditions and execute a different block of code depending on which condition is true.
- `else`: The `else` statement is used to execute a block of code if all of the previous `if` and `elif` statements evaluated to false. Use `else` when you want to provide a default action or outcome if none of the conditions in the preceding `if` and `elif` statements are true.

## Loops

Loop control flow statements are used in programming to execute a block of code repeatedly. There are several types of loop control flow statements:

- `for` loop: The `for` loop is used to execute a block of code a specified number of times. It is often used to iterate over a sequence, such as a list or an array.

- `while` loop: The `while` loop is used to execute a block of code as long as a specified condition is true. It is often used when the number of iterations is not known beforehand.

- `do-while` loop: The `do-while` loop is similar to the `while` loop, but the block of code is executed at least once, regardless of whether the condition is true or false.

- `break` statement: The `break` statement is used to exit a loop prematurely. It is often used to terminate a loop if a certain condition is met.

- `continue` statement: The `continue` statement is used to skip the current iteration of a loop and continue with the next iteration.

- `pass` statement: The `pass` statement is used as a placeholder when no action is required inside a loop. It is often used to create empty loops that will be filled in later.

```python
# Examples of control structures in Python

# Conditional statement
if x > y:
    print("x is greater than y")
elif x < y:
    print("x is less than y")
else:
    print("x and y are equal")

# Loop
for i in range(5):
    print(i)

while x < 10:
    x += 1
```
