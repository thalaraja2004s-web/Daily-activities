"""
PYTHON LOOPING STATEMENTS

Looping statements are used to execute a block of code repeatedly
until a specified condition is satisfied. Python mainly uses
'for' loop and 'while' loop for iteration.
"""


# ======================================================
# 1. FOR LOOP
# Used to iterate over a sequence like list, tuple,
# string, or range.
# ======================================================

print("FOR LOOP EXAMPLE")
print("-----------------")

for i in range(1, 6):
    print("Number:", i)



# ======================================================
# 2. WHILE LOOP
# Executes a block of code as long as the condition
# remains True.
# ======================================================

print("\nWHILE LOOP EXAMPLE")
print("------------------")

num = 1

while num <= 5:
    print("Number:", num)
    num += 1



# ======================================================
# 3. NESTED LOOP
# A loop inside another loop.
# ======================================================

print("\nNESTED LOOP EXAMPLE")
print("-------------------")

for i in range(1, 4):
    for j in range(1, 4):
        print("i =", i, ", j =", j)
