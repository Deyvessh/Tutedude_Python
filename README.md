# Task 1: basic_mathamatical_operation

This Python script is a basic calculator that takes two numbers from the user and performs four arithmetic operations: **addition**, **subtraction**, **multiplication**, and **division**. It then prints the results in a formatted manner.

```python
first_number = int(input('Enter the first number: '))
```
- `input()` prompts the user to enter a value (via keyboard).
- The entered value is treated as a string by default.
- `int()` converts that string into an integer.
- The result is stored in the variable `first_number`.

```python
second_number = int(input('Enter the second number: '))
```
- Similar to the first line, this takes another number and stores it in `second_number`.

```python
addition = first_number + second_number
```
- Adds the two numbers and stores the result in `addition`.
- Example: `10 + 5 = 15`

```python
subtraction = first_number - second_number
```
- Subtracts the second number from the first.
- Example: `10 - 5 = 5`

```python
multiplication = first_number * second_number
```
- Multiplies the two numbers.
- Example: `10 * 5 = 50`

```python
division = first_number / second_number
```
- Divides the first number by the second.
- Always returns a float.
- Example: `10 / 5 = 2.0`

```python
print(f'Addition: {addition}')
print(f'Subtraction: {subtraction}')
print(f'Multiplication: {multiplication}')
print(f'Division: {division}')
```
- These lines print the results using **f-strings**, which allow variables to be embedded directly inside the string.

**Sample Output:**
```
Addition: 15
Subtraction: 5
Multiplication: 50
Division: 2.0
```

---

# Task 2: personalized_greeting

This script collects the user's first and last name and displays a personalized greeting.

```python
first_name = input('Enter your first name: ')
```
- Prompts the user for their first name.
- Stores the input string in `first_name`.

```python
last_name = input('Enter your last name: ')
```
- Prompts the user for their last name.
- Stores the input in `last_name`.

```python
print(f'Hello, {first_name} {last_name}! Welcome to the Python program.')
```
- This line uses an f-string to format and display the personalized message.

**Sample Output:**
```
Hello, John Doe! Welcome to the Python program.
```

---

Both scripts are useful for practicing user input, basic variables, arithmetic operations, and string formatting in Python.

