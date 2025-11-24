## Python Loops

Loops allow your program to **repeat code multiple times**.  
Python provides `for` loops and `while` loops, which are used depending on the situation.

---

### 1. `for` Loops

- Used to iterate over a **sequence** (list, tuple, string, range, etc.).  
- Executes a block of code for each item in the sequence.

```python
# Example 1: Iterate over a list
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
# Output:
# apple
# banana
# cherry

# Example 2: Using range() to iterate over numbers
for i in range(5):
    print(i)
# Output:
# 0
# 1
# 2
# 3
# 4

# Example 3: Sum numbers using a for loop
total = 0
for i in range(1, 6):  # 1 to 5
    total += i
print("Sum:", total)
# Output:
# Sum: 15
```

**Key Points for `for` loops:**
- `range(start, stop, step)` generates numbers: `start` inclusive, `stop` exclusive.  
- Loops can iterate over **any iterable**: strings, lists, tuples, sets, dictionaries (keys or values).  
- Use `break` to exit the loop early and `continue` to skip the current iteration.

---

### 2. `while` Loops

- Repeats a block of code **as long as a condition is True**.  
- Useful when the number of iterations is **not known in advance**.

```python
# Example 1: Simple while loop
count = 0
while count < 5:
    print(count)
    count += 1
# Output:
# 0
# 1
# 2
# 3
# 4

# Example 2: Using break
count = 0
while True:
    print(count)
    count += 1
    if count == 3:
        break
# Output:
# 0
# 1
# 2

# Example 3: Using continue
count = 0
while count < 5:
    count += 1
    if count == 3:
        continue  # Skip printing when count is 3
    print(count)
# Output:
# 1
# 2
# 4
# 5
```

**Key Points for `while` loops:**
- Make sure the **condition will eventually become False**, otherwise the loop will run forever.  
- `break` exits the loop immediately.  
- `continue` skips the rest of the current iteration and moves to the next check.  

---

### 3. Nested Loops

- Loops inside loops are called **nested loops**.  
- Useful for **2D structures** like grids, matrices, or tables.

```python
# Example: Nested for loop
for i in range(1, 4):  # Outer loop
    for j in range(1, 4):  # Inner loop
        print(f"i={i}, j={j}")
# Output:
# i=1, j=1
# i=1, j=2
# i=1, j=3
# i=2, j=1
# i=2, j=2
# i=2, j=3
# i=3, j=1
# i=3, j=2
# i=3, j=3
```

**Tips:**
- Nested loops can be `for` inside `for`, `while` inside `while`, or mixed.  
- Be careful: nested loops can **increase execution time** quickly.  

---

✅ **Summary:**
- **`for` loop** → best for iterating over sequences with a known length.  
- **`while` loop** → best for repeating until a condition is met.  
- Use **`break`** and **`continue`** to control loop execution.  
- **Nested loops** allow multi-level iteration for more complex logic.
