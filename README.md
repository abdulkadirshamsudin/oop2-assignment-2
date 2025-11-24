## Printing in Python
#- We use the print() function to display messages on the screen.
#Example
print("What you want to print")
print("Hello World")


## Variables
#- Variables are containers used to store values such as integers, strings, floats, and booleans.

## 1. Strings
#- Strings are text values inside quotes.
#Example
# first_name = "bro"
# last_name = "shariff"
# full_name = first_name + " " + last_name
# print(full_name)


## 2. Integers (int)
#- Integers are whole numbers (positive or negative).
#- You can update integer values using operators like +=
#- type casting: converting a value to a different type (e.g., int → str).
#Example
age = 21
age += 1
print("My age is " + str(age))  # str(age) converts integer to string


## 3. Floats
#- Floats are numbers with decimal places.
#Example
height = 178.5
print("My height is " + str(height))


## 4. Booleans
#- Booleans represent True or False values.
#Example
human = False
print(human)


## Multiple Assignment
#- You can assign values to multiple variables in one line.
#Example
name, age, attractive = "shariff", 21, True

#Example
spongebob = 30
patric = 30
garry = 30

#- This is the same as writing:
spongebob = patric = garry = 30
