# python_fundamentals
Well documented implementation of core python.

# Python is a high-level, interpreted programming language known for its readable syntax and versatility. It supports multiple paradigms — procedural, object-oriented, and functional programming — making it suitable for web development, data analysis, automation, and more .

# Syntax & Structure 
Python uses indentation to define code blocks instead of braces {}. Statements end with a newline, and comments start with # for single-line or triple quotes for multi-line docstrings .
  "#" Single-line comment
  """ Multi-line
  comment """
# Variables & Data Types Variables are dynamically typed — no explicit type declaration is needed. Common types include:
1. int
2. float
3. complex
4. str(strings)
list, tuple, dict, set
bool (True/False)
x = 42 # int
y = 3.14 # float
name = "Ana" # string

# Operators Python supports:
1. Arithmetic: +, -, *, /, //, %, **
2. comparison: ==, !=, <, >, <=, >=
3. Logical: and, or, not
4. Assignment: =, +=, -=, etc.
5. Binary: &,|,~,>>,<<.
6. Identity: is, is not.
7. Membership: in, not in.

# Control Flow Conditional statements and loops control execution:
1. if
2. if-else
3. if-elif-else
4. nested-if
5. for
6. nested-for
7. while
8. do-while
9. break
10. continue
11. pass

# user define functions
def greet(name="Guest"):
  print(f"Hello, {name}!")
greet("Alice")

# Collections
1. Lists: Mutable sequences
2. Tuples: Immutable sequences
3. Dictionaries: Key-value pairs
4. Sets: Unordered unique elements

# File Handling Python can read/write files easily:
with open("data.txt", "w") as f:
f.write("Hello File")
