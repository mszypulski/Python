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
