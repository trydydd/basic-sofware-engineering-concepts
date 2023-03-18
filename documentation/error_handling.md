# Error Handling

Error handling is used to manage exceptions or errors that may occur during the execution of a program. Common error handling techniques include:

- Try-except blocks
- Raising exceptions

```python
# Example of error handling in Python

try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")

def divide(a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero")
    return a / b
```
