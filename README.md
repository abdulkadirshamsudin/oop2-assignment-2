# Python Basics

This section introduces fundamental Python concepts including printing output, variables, data types, and multiple assignment. Each concept includes a short explanation and a clear example.

---

# Printing Messages

Python uses the `print()` function to display text or values on the screen.

### Example:
```python
print("What you want to print")
print("Hello World")
Variables
Variables are containers that store data values. Common data types include:

String (text)

Integer (whole numbers)

Float (decimal numbers)

Boolean (True or False)

1. Strings
Strings store text data. They are written inside quotes.

Example:
python
Copy code
first_name = "bro"
last_name = "shariff"
full_name = first_name + " " + last_name
print(full_name)
2. Integers
Integers store whole numbers. You can modify them using arithmetic operations.

Example:
python
Copy code
age = 21
age += 1
print("My age is " + str(age))  # type casting with str()
Note: You must convert numbers to strings when joining them with text (type casting).

3. Floats
Floats represent numbers with decimals.

Example:
python
Copy code
height = 178.5
print("My height is " + str(height))
4. Booleans
Booleans represent True or False values.

Example:
python
Copy code
human = False
print(human)
Multiple Assignment
Python allows assigning values to multiple variables in a single line.

Example 1:
python
Copy code
name, age, attractive = "shariff", 21, True
Example 2:
You can assign one value to several variables at once:

python
Copy code
spongebob = patrick = gary = 30
This sets all three variables to the value 30.

Copy code
