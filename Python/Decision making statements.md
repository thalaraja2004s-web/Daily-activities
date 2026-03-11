"""
PYTHON DECISION MAKING STATEMENTS

Decision making statements are used to execute different blocks of code
based on a condition. Python uses if, elif, and else statements for
decision making.
"""


# ==================================================
# 1. IF STATEMENT
# Executes a block of code if the condition is True
# ==================================================

num = 10

if num > 0:
    print("Number is positive")


# ==================================================
# 2. IF - ELSE STATEMENT
# Executes one block if condition is True
# otherwise executes another block
# ==================================================

num = 5

if num % 2 == 0:
    print("Even Number")
else:
    print("Odd Number")


# ==================================================
# 3. IF - ELIF - ELSE STATEMENT
# Used to check multiple conditions
# ==================================================

marks = 75

if marks >= 90:
    print("Grade: A")
elif marks >= 60:
    print("Grade: B")
else:
    print("Grade: C")


# ==================================================
# 4. NESTED IF STATEMENT
# An if statement inside another if statement
# ==================================================

num = 15

if num > 0:
    if num % 3 == 0:
        print("Positive number and divisible by 3")
