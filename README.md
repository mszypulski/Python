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

print(str)          # Prints complete string
print(str[0])       # Prints first character of the string
print(str[2:5])     # Prints characters starting from 3rd to 5th
print(str[2:])      # Prints string starting from 3rd character
print(str * 2)      # Prints string two times
print(str + "TEST") # Prints concatenated string
print(len(str))     # Prints the length of the string
```
Output:

```python
Hello World!
H
llo
llo World!
Hello World!Hello World!
Hello World!TEST
12
```
## Operators

Arithmetic Operators
```python
x + y          # Addition +
x - y          # Substraction -
x * y          # Multiplication *
x / y          # Division /
x % y          # Modulus %
x ** y         # Exponentiation **
x // y         # Floor division //
```
Assignment Operators
```python
x = 5       # x = 5	
x += 3	    # x = x + 3	
x -= 3	    # x = x - 3	
x *= 3	    # x = x * 3	
x /= 3	    # x = x / 3	
x %= 3	    # x = x % 3	
x //= 3	    # x = x // 3	
x **= 3	    # x = x ** 3	
x &= 3	    # x = x & 3	
x |= 3	    # x = x | 3	
x ^= 3	    # x = x ^ 3	
x >>= 3	    # x = x >> 3	
x <<= 3	    # x = x << 3
```
Comparison Operators
```python
x == y  # Equal == 	
x != y  # Not equal != 	
x > y   # Greater than > 	
x < y   # Less than <	
x >= y  # Greater than or equal to >=	
x <= y  # Less than or equal to <=
```
Logical Operators
```python
and   # Returns True if both statements are true x < 5 and  x < 10	
or    # Returns True if one of the statements is true x < 5 or x < 4	
not   # Reverse the result, returns False if the result is true not(x < 5 and x < 10)
```
Identity Operators
```python
is      # Returns true if both variables are the same object x is y	
is not  # Returns true if both variables are not the same object x is not y
```
Membership Operators
```python
in      # Returns True if a sequence with the specified value is present in the object	x in y	
not in  # Returns True if a sequence with the specified value is not present in the object	x not in y
```
Bitwise Operators
```python
&     # AND	Sets each bit to 1 if both bits are 1
|     # OR	Sets each bit to 1 if one of two bits is 1
^     # XOR	Sets each bit to 1 if only one of two bits is 1
~     # NOT	Inverts all the bits
<<    # Zero fill left shift	Shift left by pushing zeros in from the right and let the leftmost bits fall off
>>    # Signed right shift	Shift right by pushing copies of the leftmost bit in from the left, and let the rightmost bits fall off
```
### Lists
A list is a collection which is ordered and changeable.

```python
thislist = ["apple", "banana", "cherry"]
print(thislist)
```
Output:

```python
['apple', 'banana', 'cherry']
```
### Tuples
A tuple is a collection which is ordered and unchangeable.

```python
thistuple = ("apple", "banana", "cherry")
print(thistuple)
```
Output:

```python
('apple', 'banana', 'cherry')
```
### Sets
A set is a collection which is unordered and unindexed.

```python
thisset = {"apple", "banana", "cherry"}
print(thisset)
```
Output:

```python
{'apple', 'banana', 'cherry'}
```
### Dictionaries
A dictionary is a collection which is unordered, changeable and indexed.

```python
thisdict =	{
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict)
```
Output:

```python
{'brand': 'Ford', 'model': 'Mustang', 'year': 1964}
```

### If
If statement.

```python
a = 33
b = 200
if b > a:
  print("b is greater than a")
```
Output:

```python
b is greater than a
```
### Elif

```python
a = 33
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
```
Output:

```python
a and b are equal
```

### Else

```python
a = 200
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")
```
Output:

```python
a is greater than b
```
### If ... else
```python
a = 200
b = 33
if b > a:
  print("b is greater than a")
else:
  print("b is not greater than a")
```
Output:

```python
b is not greater than a
```
