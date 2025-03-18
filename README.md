ASSIGNMENT 1 

TASK 2 

# Taking input from the user
first_name = input("Enter your first name: ")
last_name = input("Enter your last name: ")

# Concatenating first name and last name to form full name
full_name = first_name + " " + last_name

# Printing the personalized greeting message
print(f"\nHello, {full_name}! Welcome!")


ASSIGNMENT 1 

TASK 1

# Taking input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Performing basic mathematical operations
addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2
if num2 != 0:
    division = num1 / num2
else:
    division = "Undefined (division by zero is not allowed)"

# Displaying the results
print("\nResults of Basic Mathematical Operations:")
print(f"Addition: {num1} + {num2} = {addition}")
print(f"Subtraction: {num1} - {num2} = {subtraction}")
print(f"Multiplication: {num1} * {num2} = {multiplication}")
print(f"Division: {num1} / {num2} = {division}")
