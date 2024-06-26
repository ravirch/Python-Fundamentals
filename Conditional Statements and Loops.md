### Python Fundamentals - Part 3

#### 12. Conditional Statement
Conditional statements (`if`, `elif`, `else`) are used to perform different actions based on different conditions.

**Example:**
```python
x = 10
if x > 0:
    print("x is positive")
elif x < 0:
    print("x is negative")
else:
    print("x is zero")
```

#### 13. Logical Operators
Logical operators (`and`, `or`, `not`) are used to combine conditional statements.

**Example:**
```python
x = 5
y = 10
if x > 0 and y > 0:
    print("Both x and y are positive")

if x > 0 or y < 0:
    print("At least one of x or y is positive")

if not (x < 0):
    print("x is not negative")
```

#### 14. `in` / `not in` Keywords
The `in` keyword checks if a value is present in a sequence (like a string, list, tuple, etc.), while `not in` checks if it is not present.

**Example:**
```python
s = "hello"
print('e' in s)  # True
print('a' not in s)  # True
```

#### 15. Loops in Python
Loops are used to iterate over a sequence (like a list, tuple, dictionary, set, or string).

**Example:**
- **For Loop:**
  ```python
  fruits = ["apple", "banana", "cherry"]
  for fruit in fruits:
      print(fruit)
  ```

- **While Loop:**
  ```python
  i = 0
  while i < 5:
      print(i)
      i += 1
  ```

#### 16. Control Statement
Control statements like `break`, `continue`, and `pass` are used to alter the flow of loops.

**Example:**
```python
for i in range(5):
    if i == 3:
        break  # Exit the loop when i is 3
    print(i)

for i in range(5):
    if i == 3:
        continue  # Skip the iteration when i is 3
    print(i)

for i in range(5):
    pass  # Do nothing
```

---
