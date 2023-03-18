# Error Handling

Error handling is used to manage exceptions or errors that may occur during the execution of a program. Common error handling techniques include:

## Try-except blocks

Try-except blocks are used to catch and handle exceptions that occur during program execution:
```python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")
```

In this example, the try block contains the code that may raise an exception, and the except block contains the code that handles the exception if it occurs. ZeroDivisionError is the specific exception that is being caught and handled. If an exception is raised in the try block, the code in the except block is executed.

## Raising exceptions
Another approach to error handling is to raise exceptions when errors occur. This allows you to control how errors are handled and provide more information about the error. 

```python
def divide(a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero")
    return a / b
```
n this example, the raise statement raises a ValueError exception with a message that describes the error. If the condition is true, the exception is raised and the program stops executing.