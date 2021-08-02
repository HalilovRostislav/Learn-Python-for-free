# Data types. Variables

A variable is an area of ​​memory that stores information. Variable names must begin with an alphabetic character or an underscore (_) character.
Also, the name of the variable can contain a number (name1).
In addition, the name of the variable should not be from the name of Python keywords.

[and, as, assert, break, class, continue, def, del, elif, else, except, False, finally, for, from, global, if, import, in, is, lambda, None, nonlocal, not, or, pass, raise, return, True, try, while, with, yield.]

#

* boolean - boolean True or False
* int - represents an integer, such as 1, 4, 8, 50.
* float - represents a floating point number, for example 1.2 or 34.76
* complex - complex numbers
* str - strings, for example "hello". In Python 3.x, strings represent a set of Unicode characters
* bytes - a sequence of numbers in the range 0-255
* byte array - an array of bytes, similar to bytes, with the difference that it can change
* list - list
* tuple - tuple
* set - an unordered collection of unique objects
* frozen set - same as set, only immutable
* dict - a dictionary where each element has a key and a value

# Operations

An operation is the execution of any actions with data, which in this case are called operands.

![image](https://user-images.githubusercontent.com/70141250/127199510-798cce84-63c6-4839-9d18-5a1ff755803c.png)

So in mathematics and programming, the plus symbol is an operator for adding numbers. In the case of strings, the same operator performs a concatenation operation, that is, a join.

```
>>> 10 + 10
20
>>> 'Hello,' + 'World!'
Hello,World!
```
If you try to add a number to a string, you will get an error.

```
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: unsupported operand type(s) for +: 'int' and 'str'
```

# Variables

A variable is the simplest named data structure in which an intermediate or final result of a program can be stored.
In Python, as in most other languages, the relationship between data and variables is established using the ```=``` sign. This operation is called assignment.
For exemple: ```a = 5```
in this example, the value ```5``` is assigned to the variable ```a```

![image](https://user-images.githubusercontent.com/70141250/127202632-e984a314-9e9d-44a6-a644-82423b625906.png)


# example of working with variables

```
>>> a = 100
>>> b = 5
>>> b = 7
>>> a * b
700
```
