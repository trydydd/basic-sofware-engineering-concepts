# Input and Output

Input and output operations are used to interact with the user, read data from files, or write data to files.

```python
# Example of input and output in Python

# Input from the user
name = input("Enter your name: ")

# Output to the user
print(f"Hello, {name}!")

# Read from a file
with open("input.txt", "r") as file:
    content = file.read()

# Write to a file
with open("output.txt", "w") as file:
    file.write("Hello, World!")
```
