### Python Fundamentals - Part 2

#### 7. `input()`
The `input()` function reads a line from input (usually from the user), converts it into a string, and returns it.

**Example:**
```python
name = input("Enter your name: ")
print("Hello, " + name + "!")
```

#### 8. String Formatting
String formatting allows you to inject variables into strings using placeholders.

**Example:**
```python
name = "Alice"
age = 25
formatted_string = f"Name: {name}, Age: {age}"
print(formatted_string)
```

#### 9. String Indexing
Strings are indexed with the first character at index 0. Negative indexing starts from the end.

**Example:**
```python
s = "Hello"
print(s[0])  # 'H'
print(s[-1]) # 'o'
```

#### 10. Methods on String
Python provides various methods to manipulate strings.

**Example:**
```python
s = "hello world"
print(s.upper())     # 'HELLO WORLD'
print(s.lower())     # 'hello world'
print(s.title())     # 'Hello World'
print(s.replace("world", "Python")) # 'hello Python'
print(s.split())     # ['hello', 'world']
```

#### 11. Assignment Operator like `+=`, `-=`
Assignment operators are used to update the value of a variable.

**Example:**
```python
x = 5
x += 3  # Equivalent to x = x + 3
print(x)  # 8

y = 10
y -= 2  # Equivalent to y = y - 2
print(y)  # 8
```

---
