# internorbit_task
# Simple Calculator in Python

# Get input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Show operation options
print("Select an operation:")
print(" + for addition")
print(" - for subtraction")
print(" * for multiplication")
print(" / for division")

# Get the operation from the user
operation = input("Enter your operation: ")

# Perform calculation based on operation
if operation == '+':
    result = num1 + num2
    print(f"Result: {num1} + {num2} = {result}")
elif operation == '-':
    result = num1 - num2
    print(f"Result: {num1} - {num2} = {result}")
elif operation == '*':
    result = num1 * num2
    print(f"Result: {num1} * {num2} = {result}")
elif operation == '/':
    if num2 != 0:
        result = num1 / num2
        print(f"Result: {num1} / {num2} = {result}")
    else:
        print("Error: Division by zero is not allowed.")
else:
    print("Invalid operation selected.")
