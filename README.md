# input_in_python
# Learn more about input
# In this exercise we learn more about "input" in Python.
# First version:

print("How old are you?", end=' ')
age = input()
print("How tall are you?", end=' ')
height = input()
print("How much do you weigh?", end=' ')
weight = input()

print(f"So, you are {age} old, {height} tall and {weight} heavy.")

# WARNING! We put an end=' ' at the end of each print line. 
# This tells print to not change the line with a newline character.

# a new version that directly assigns an input from the user to a variable.
age = input('How old are you? ')
height = input('How tall are you? ')
weight = input('How much do you weight? ')

print(f"So, you're {age} old, {height} tall and {weight} heavy.")

