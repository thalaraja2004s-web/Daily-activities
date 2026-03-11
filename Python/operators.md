"""
Python Operators Examples
An operator is a symbol used to perform operations on variables and values.
"""

# --------------------------------------------------
# 1. Arithmetic Operators
# Used to perform mathematical calculations.
# --------------------------------------------------

a = 10
b = 5

print("Arithmetic Operators")
print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)
print("Modulus:", a % b)
print("Exponent:", a ** b)
print("Floor Division:", a // b)


# --------------------------------------------------
# 2. Comparison Operators
# Used to compare two values and return True or False.
# --------------------------------------------------

x = 7
y = 10

print("\nComparison Operators")
print("Equal:", x == y)
print("Not Equal:", x != y)
print("Greater Than:", x > y)
print("Less Than:", x < y)
print("Greater or Equal:", x >= y)
print("Less or Equal:", x <= y)


# --------------------------------------------------
# 3. Logical Operators
# Used to combine conditional statements.
# --------------------------------------------------

p = True
q = False

print("\nLogical Operators")
print("AND:", p and q)
print("OR:", p or q)
print("NOT:", not p)


# --------------------------------------------------
# 4. Assignment Operators
# Used to assign values to variables.
# --------------------------------------------------

num = 10

print("\nAssignment Operators")

num += 5
print("Add and Assign:", num)

num -= 3
print("Subtract and Assign:", num)

num *= 2
print("Multiply and Assign:", num)

num /= 4
print("Divide and Assign:", num)


# --------------------------------------------------
# 5. Membership Operators
# Used to check whether a value exists in a sequence.
# --------------------------------------------------

numbers = [10, 20, 30, 40]

print("\nMembership Operators")
print("20 in list:", 20 in numbers)
print("50 not in list:", 50 not in numbers)


# --------------------------------------------------
# 6. Identity Operators
# Used to compare the memory location of two objects.
# --------------------------------------------------

a = 10
b = 10

print("\nIdentity Operators")
print("a is b:", a is b)
print("a is not b:", a is not b)
