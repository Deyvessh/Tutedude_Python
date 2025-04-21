
Task 1: basic_mathamatical_operation

This Python script is a basic calculator that takes two numbers from the user and performs four 
arithmetic operations: addition, subtraction, multiplication, and division. 
It then prints the results in a formatted manner.

first_number = int(input('Enter the first number: '))

= input() prompts the user to enter a value (e.g., via keyboard).
= Whatever the user types is treated as a string by default.
= int() converts that string into an integer.
= The result is stored in the variable first_number.

second_number = int(input('Enter the second number: '))
= Similar to the first line, this takes another number as input and stores it in second_number.

addition = first_number + second_number
= Adds the two numbers and stores the result in addition.
= For example: 10 + 5 = 15

subtraction = first_number - second_number
= Subtracts the second number from the first and stores it in subtraction.
= Example: 10 - 5 = 5

multiplication = first_number * second_number
= Multiplies the two numbers.
= Example: 10 * 5 = 50

division = first_number / second_number
= Divides the first number by the second and stores the result in division.
= Example: 10 / 5 = 2.0
= Please Note: This always returns a float (e.g., 2.0, not 2).

print(f'Addition: {addition}')
print(f'Subtraction: {subtraction}')
print(f'Multiplication: {multiplication}')
print(f'Division: {division}')
= These lines print the results using f-strings, which allow variable values to be embedded directly into strings.

The output will look like this:
Addition: 15
Subtraction: 5
Multiplication: 50
Division: 2.0



Task 2: personalized_greeting

first_name = input('Enter your first name: ')
= input() displays the prompt message 'Enter your first name: ' to the user.
= The user types something, and that string is returned.
= Whatever is typed is stored in the variable first_name.

last_name = input('Enter your last name: ')
= Similar to the first line, this gets the user's last name.
= Stored in the variable last_name.

print(f'Hello, {first_name} {last_name}! Welcome to the Python program.')
= This is a formatted string literal (or f-string).
= It lets you insert variable values directly inside the string using {}.

The output will be:
= Hello, John Doe! Welcome to the Python program.

