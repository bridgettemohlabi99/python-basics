# Variables
```python
var_name = "Hello"
```

# Integers
```python
integer = 7
```

# Floating Numbers
```python
float_num = 2.718
```

# Boolean Values 
```python
bool_val = False  # Boolean values use capitalized 'True' and 'False'
```

# Math Operators
```python
addition = 4 + 5
subtraction = 5 - 2
division = 7 / 2
multiplication = 3 * 8
```

# Assignment Operators
```python
add_assign = 5
add_assign += 7  # Equivalent to: add_assign = add_assign + 7
```

# Printing Values
```python
example_1 = 3.1415
print(example_1)
```

# Strings
```python
ex_8 = "orange"
# Indexing (zero-based)
print(ex_8[2])  # Output: "a"
```

# String Slicing
```python
ex = "apricots"
print(ex[:3])   # Output: "apr" (3 is exclusive)
print(ex[2:5])  # Output: "ric"
print(ex[4:])   # Output: "cots"
```

# String Concatenation
```python
# Adding strings together using the '+' operator
print("pecan" + " " + "pie")  # Output: "pecan pie"
concatenated = "R2" + "-" + "D2"
print(concatenated)  # Output: "R2-D2"
print(concatenated[3])  # Output: "D"
print(concatenated[1:4])  # Output: "2-D"
```

# Escape Sequences
```python
# Tab character (\t)
print("This\tis\ta\tlot\tof\tspace.")  # Output: "This    is    a    lot    of    space."

# Newline character (\n)
print("line one\nline two")
# Output:
# line one
# line two
```

# Functions

## Defining a Function
```python
def function_name():
    print(2 + 2)

function_name()  # Calling the function, Output: 4
```

## Function Parameters
```python
def function_name(parameter):
    print(parameter + 2)

function_name(8)  # Output: 10
```
```python
def default_example(num1=7, num2=8):
    print(num1 * num2)

default_example(2)  # Output: 16 because num1 changed to 2
```

## Return
**We use return when you want your function to produce something that can be used in expressions or assigned to a variable rather than just printed**
```python
def default_example(num1=7, num2=8):
    return num1 * num2

print(default_example() + 44)  # Output: 100
```

# If Statements
## Syntax
```python
if condition:
    statement_to_execute
```

## Example
```python
veg = input("Type the name of a vegetable: ")

if veg == "corn":
    print("The vegetable is corn.")  # Output: The vegetable is corn.
```



