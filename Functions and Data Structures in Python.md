### Python Fundamentals - Part 4

#### 17. Function
Functions are defined using the `def` keyword and are used to encapsulate reusable code blocks.

**Example:**
```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Alice"))  # "Hello, Alice!"
```

#### 18. Return vs Print Statement in Function
The `return` statement exits a function and returns a value, while `print` simply outputs a value to the console.

**Example:**
```python
def add(a, b):
    return a + b

result = add(3, 4)
print(result)  # 7

def display_sum(a, b):
    print(a + b)

display_sum(3, 4)  # 7 (printed, but not returned)
```

#### 19. Split Function on String
The `split()` method splits a string into a list based on a delimiter.

**Example:**
```python
s = "hello world"
words = s.split()
print(words)  # ['hello', 'world']

s = "apple,banana,cherry"
fruits = s.split(',')
print(fruits)  # ['apple', 'banana', 'cherry']
```

#### 20. Data Structures in Python: List
Lists are ordered, mutable collections of items. Major functions include:

**Example:**
```python
fruits = ["apple", "banana", "cherry"]
print(fruits[0])  # 'apple'

# Append
fruits.append("orange")
print(fruits)  # ['apple', 'banana', 'cherry', 'orange']

# Pop
fruits.pop()
print(fruits)  # ['apple', 'banana', 'cherry']

# Remove
fruits.remove("banana")
print(fruits)  # ['apple', 'cherry']

# Insert
fruits.insert(1, "banana")
print(fruits)  # ['apple', 'banana', 'cherry']
```
---
