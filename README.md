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

age = int(input('How old are you? '))
print(f"You are {age} years old")
print("Press <Enter> to continue.")
input()
age2 = int(input('What is the age of your closest cousin? '))
print(f"He/she is {age2} years old.")
print("Press <Enter> to continue.")
input()
print(f"You have {age + age2} years old together.")
