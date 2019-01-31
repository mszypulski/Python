![Python in a pill](/python_logo.jpeg "Python")

# Python in a pill
written by Mariusz Szypulski

## First program

```python
print("Hello, World!")
```
Output:

```python
Hello, World!
```

## Indentations

Python uses indentation to indicate a block of code.

```python
if 1 > 0:
  print("One is greater than zero!")
```
Output:

```python
One is greater than zero!
```
Python will give you an error if you skip the indentation:

```python
if 1 > 0:
print("One is greater than zero!")
```

Output:

```python
IndentationError: expected an indented block
```

## Comments

```python
#This is an oneline comment.
```
```python
"""This is a 
multiline comment."""
```
## Variables

A variable is created the moment you first assign a value to it.

* A variable name must start with a letter or the underscore character
* A variable name cannot start with a number
* A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
* Variable names are case-sensitive (age, Age and AGE are three different variables)

```python
x = 3
y = "Mariusz"
print(x)
print(y)
```
Output:

```python
3
Mariusz
```
Python allows you to assign a single value to several variables simultaneously. 

```python
x = b = c = 1
print(a)
print(b)
print(c)
```
Output:

```python
1
1
1
```

You can also assign multiple objects to multiple variables. 

```python
a,b,c = 1,2,"Mariusz"
print(a)
print(b)
print(c)
```
Output:

```python
1
2
Mariusz
```

Variables can change type after they have been set.

```python
x = 5 # x is of type int
x = "Mariusz" # x is now of type str
print(x)
```
Output:

```python
Mariusz
```
## Standard Data Types

Python has five standard data types:

* Numbers
* String
* List
* Tuple
* Dictionary

## Python Numbers

Python supports three different numerical types:

* int (signed integers)
* float (floating point real values)
* complex (complex numbers)

```python
a = 10 #int
c = 0.0 #float
d = 3.14j #complex
```
## Casting

Python is an object-orientated language and uses classes to casting data types.

Casting in python is done using constructor functions:

* int() - constructs an integer number from an integer literal, a float literal (by rounding down to the previous whole number), or a string literal (providing the string represents a whole number)
* float() - constructs a float number from an integer literal, a float literal or a string literal (providing the string represents a float or an integer)
* str() - constructs a string from a wide variety of data types, including strings, integer literals and float literals

Integers:
```python
x = int(1)   # x will be 1
y = int(2.8) # y will be 2
z = int("3") # z will be 3
```

Floats:
```python
x = float(1)     # x will be 1.0
y = float(2.8)   # y will be 2.8
z = float("3")   # z will be 3.0
w = float("4.2") # w will be 4.2
```
Strings:
```python
x = str("s1") # x will be 's1'
y = str(2)    # y will be '2'
z = str(3.0)  # z will be '3.0'
```
## Strings

```python
x = 'hello'
y = "hello" 
print(x)
print(y)
```
Output:

```python
hello
hello
```

```python
str = 'Hello World!'

print str          # Prints complete string
print str[0]       # Prints first character of the string
print str[2:5]     # Prints characters starting from 3rd to 5th
print str[2:]      # Prints string starting from 3rd character
print str * 2      # Prints string two times
print str + "TEST" # Prints concatenated string
```
Output:

```python
Hello World!
H
llo
llo World!
Hello World!Hello World!
Hello World!TEST
```
